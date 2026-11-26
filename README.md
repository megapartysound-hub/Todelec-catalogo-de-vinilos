# Tienda de vinilos

Catálogo de discos con categorías, carrito y cierre de compra por WhatsApp.

## Archivos
- `index.html`: la página (liviana).
- `data.json`: los discos, las tapas, las categorías y la configuración. Acá se guardan todos los cambios.
- `.nojekyll`: archivo vacío que necesita GitHub Pages.

## Publicar gratis en GitHub Pages (queda online en una dirección fija)
1. Creá una cuenta en github.com.
2. New repository: poné un nombre (por ejemplo `vinilos`) y marcá Public.
3. Add file → Upload files: subí `index.html`, `data.json` y `.nojekyll` (descomprimí el zip primero). Commit changes.
4. Settings → Pages → Build and deployment: Deploy from a branch, rama `main`, carpeta `/ (root)`, Save.
5. A los 1 o 2 minutos tu tienda está en `https://TU-USUARIO.github.io/vinilos/`. Esa es la dirección que compartís; se ve desde cualquier celular o computadora.

## Entrar como administrador
1. Abajo de todo tocá 🔒 Administrar. La clave inicial es `cambiame`.
2. En Ajustes cambiá la clave, revisá el número de WhatsApp y el aviso de la página principal.

## Subir discos nuevos todos los días
1. En GitHub: Settings (tu cuenta) → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token.
2. Elegí solo tu repositorio y el permiso Contents: Read and write.
3. En la tienda, Ajustes → Conexión con GitHub: cargá tu usuario, el nombre del repositorio y el token. Se guardan solo en ese navegador.
4. Cargá discos, tapas y categorías y tocá Guardar y publicar. Se actualiza online en 1 o 2 minutos.

## Importante
- La clave solo evita curiosos. La protección real es el token: sin él nadie puede cambiar tu catálogo. No lo subas al repositorio ni lo compartas.
- Tocá Descargar copia de vez en cuando para tener un respaldo.
- Con muchos discos y fotos data.json se hace pesado (hoy unos 4 MB). Si la página tarda en abrir en celulares, avisame y se pasan las tapas a archivos aparte.
