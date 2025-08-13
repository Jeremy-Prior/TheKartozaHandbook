# Frameworks

Standardise on the frameworks used to encourage collaboration and efficiency.

## Cross-platform

- [Qt](https://www.qt.io/product/framework) — C++ / Python (PyQt / PySide)
- [React Native](https://reactnative.dev/) — JavaScript / TypeScript
- [Flutter](https://flutter.dev/) — Dart
- [Quasar](https://quasar.dev/) — JavaScript, Vue-based
- [BeeWare](https://beeware.org/) — Python
- [Kivy](https://kivy.org/) — Python

## Desktop

- Prefer **Qt** for native apps.
- [Tauri](https://tauri.studio) — JavaScript / Rust (Rust backend + JS frontend; alternative to Electron).

## Mobile

If you’re not going fully native, use a cross-platform framework.

## Web

- **Preferred:** **Django (Python)** — batteries included; pair with **Django REST Framework** for APIs.
- **Flask (Python):** lightweight microservice or gateway.
- **FastAPI (Python):** async-first REST APIs; use when ASGI/async is needed.
- **Express (JavaScript):** server-side Node.js.
- **Next.js (JavaScript):** server-side React.

## Docs

Use **Material for MkDocs** for project documentation.

## Jamstack

Default to **Hugo**.

## GIS

- **Frontend:** MapLibre GL JS, OpenLayers, Leaflet, CesiumJS, Turf.js
- **Backend:** GeoDjango, pg_featureserv, pg_tileserv

## UI

Consistent component libraries improve quality and speed.

### CSS frameworks
- **Bootstrap**
- **Bulma**
- **Tailwind CSS**

### Component libraries
- **React (web):** Chakra UI or Material UI

> Choosing outside these defaults is possible, but expect lower momentum and fewer collaborators. Document rationale in the project README.
