# O-CLOÜD — Frontend estático

Esta carpeta es una copia independiente de la interfaz de O-CLOÜD, preparada para GitHub Pages. No requiere Node.js, npm, build ni servicios externos: GitHub Pages sirve `index.html` directamente.

## Publicar con GitHub Pages

1. Crea un repositorio de GitHub para esta versión estática.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`; guarda.
5. Abre la URL que GitHub Pages indique.

## Qué incluye

- Pantallas Inicio, Closet, Outfits, Perfil, Estilista y Privacidad.
- Diseño responsive basado en la identidad visual de O-CLOÜD.
- Guardado local de prendas, fotografías, outfits y perfil mediante `IndexedDB` y `localStorage`.
- Filtros de Closet y vista previa de fotografías.

## Diferencias de la versión estática

Esta carpeta no reemplaza ni modifica el proyecto Next.js original. Al no tener servidor, Supabase ni rutas API, esta versión no ofrece cuentas, sincronización entre dispositivos, permisos de almacenamiento en la nube, procesamiento de Clipdrop, modelos 3D ni funciones de OpenAI. Los datos quedan solo en el navegador y se borran si se eliminan sus datos del sitio.

No contiene claves, archivos `.env`, dependencias ni migraciones.
