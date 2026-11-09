# Consulta de mesas — versión sin base de datos

Esta versión es una página estática: no usa Supabase, cuentas, contraseñas ni base de datos.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Crea un repositorio en https://github.com/.
3. Sube `index.html` a la raíz del repositorio.
4. Entra en Settings → Pages.
5. En Build and deployment, elige Deploy from a branch.
6. Selecciona `main` y `/(root)`, y guarda.
7. GitHub te mostrará el enlace público de la página.

## Cambiar nombres o mesas
1. Abre `index.html` con un editor de texto.
2. Busca la sección `const personas = [`.
3. Cambia los nombres y mesas respetando este formato:
   `{ nombre: "Nombre Apellido", mesa: 1 },`
4. Guarda el archivo y vuelve a subirlo a GitHub reemplazando el anterior.

## Importante: cómo funciona sin base de datos
- Todos los visitantes ven el mismo listado que está escrito en `index.html`.
- Los invitados solo pueden consultar; no pueden modificar los datos desde la página.
- Para cambiar nombres o mesas para todos, debes editar el archivo y volver a publicarlo.
- No hay inicio de sesión ni datos compartidos en tiempo real.
- El listado de ejemplo contiene nombres ficticios; reemplázalos por los datos reales antes de compartir el enlace.
