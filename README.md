# Trading Analysis Pro

Este repositorio contiene la aplicación de una sola página **Trading Analysis Pro**.

## Ejecutar la aplicación localmente

1. Abre el archivo `index.html` directamente en tu navegador.
2. Opcionalmente puedes servirlo desde un servidor estático para evitar restricciones de CORS:
   ```bash
   python3 -m http.server 8000
   ```
   Luego entra en `http://localhost:8000/index.html`.

## Subir el código a tu repositorio de GitHub

1. Crea un repositorio vacío en tu cuenta de GitHub.
2. Desde esta carpeta (`/workspace/analistapro`), agrega el remoto:
   ```bash
   git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
   ```
3. Empuja la rama actual (`work`) o la rama que prefieras al repositorio remoto:
   ```bash
   git push -u origin work
   ```
   También puedes empujar a `main` si lo deseas:
   ```bash
   git push -u origin work:main
   ```
4. Verifica en GitHub que aparezcan `index.html` y `README.md`.

## Contenido principal

- `index.html`: archivo auto-contenido con HTML, CSS (Tailwind vía CDN) y JavaScript de la aplicación.
- `README.md`: instrucciones de ejecución y despliegue.

