# 🧭 Herramienta de seguimiento — Ruta de Formación Docente 2026 (MINED)

Aplicación web (PWA) para que cualquier docente o directivo del Ministerio de Educación, Ciencia y Tecnología (El Salvador) pueda **organizar su proceso de formación 2026**, marcar lo que ya completó y acceder rápido a todos los formularios de evidencia oficiales.

> Esta herramienta es un **complemento de apoyo**. Los formularios oficiales, el portafolio digital y las evidencias son responsabilidad de cada docente.

---

## 🎯 Qué incluye

- **Checklist completo desde cero:** ruta de Bloques 1 → 16 + separatas pedagógicas + formaciones prioritarias + Portafolio Narrativo.
- **Selector de nivel y rol:** los ítems se filtran según el nivel (Primera Infancia, Primaria, Secundaria, Media Técnica) o rol (docente / directivo), porque **los materiales y formularios difieren por nivel**, aunque la ruta formativa sea la misma.
- **Marcado rápido:** casilla de "listo" y botón de desmarcar en cada ítem.
- **Gráficos de progreso:** dona de avance global y barras por fase.
- **Copia de seguridad:** exportar / importar el checklist en `.json` para no perder el avance.
- **Compartir:** enlace que incluye el estado del checklist, para que un compañero parta de tu avance.
- **PWA instalable:** se puede añadir a la pantalla de inicio y funciona sin conexión.

---

## 🧭 La ruta formativa 2026

| Fase | Periodo | Contenido |
|---|---|---|
| 0 | Transversal | Formaciones prioritarias: Antisoborno, SIGES, IA de Google |
| 1 | Enero 2026 | Franja de Orientaciones Pedagógicas — Bloques 1, 2 y 3 (orientaciones curriculares, "Conociendo Mis Logros", planificación) |
| 2 | Febrero – Marzo | Bloques 4, 5, 6 y 7 |
| 3 | Abril – Mayo | Separata n.°7 (Aprendizaje Activo) y Bloques 8, 9, 10 |
| 4 | Junio – Julio | Separata n.°8 (Aprendamos con autonomía), Bloques 11, 12, 13 y orientaciones de la estrategia |
| 5 | Agosto – Octubre | Separata n.°9 (El viaje de crecer), Bloques 14, 15, 16 y Portafolio Narrativo (3 entregables) |

**Importante:** la *ruta* es común para todo el personal docente, pero los *materiales y formularios de evidencia* se publican por nivel. Additionally, docentes de Lenguaje y Matemática (7.º a bachillerato) que participan en la Ruta para la Modernización Educativa no realizan esta ruta de Fortalecimiento, sino las directrices de esa ruta.

---

## 🛠️ Uso local

```bash
cd <carpeta-del-proyecto>
python3 -m http.server 8000
# abrir http://localhost:8000
```

## 🚀 Deploy en Vercel

```bash
npx vercel --token <TOKEN> --prod --project <nombre-del-proyecto> --create-if-missing
```

O conectar el repositorio en el dashboard de Vercel para **auto-deploy** en cada `push` a `main`.

## 📁 Estructura

```
├── index.html      # la aplicación (HTML + CSS + JS en un solo archivo)
├── manifest.json   # configuración PWA
├── sw.js           # service worker (network-first, cache de respaldo offline)
├── icon.svg        # ícono de la app
└── README.md
```

---

## 📞 Soporte institucional

soporte1@clases.edu.sv · soporte2@clases.edu.sv · soporte3@clases.edu.sv · Tel. 2410-7030
