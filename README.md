# Frontend Boilerplate

Dar inicio a un proyecto web en estos tiempos lleva tiempo tenerlo, teniendo el flujo de trabajo adecuado con las herramientas de construcción y paquetes como ayuda para lograrlo. No nos compliquemos más con ese flujo y vayamos de una vez con lo más importante que es el código del proyecto en particular, gracias a este kit de inicio.

basado en el repositorio de Jonathan MirCha

- [Repositorio](git://github.com/jonmircha/frontend-components-boilerplate.git)

## Librerias frontend

- [Materialize](https://materializecss.com/)

## Instalación

```bash
# clona el repositorio
git clone https://github.com/lucotmo/frontend-boilerplate.git
```

### Instalación de yarn

- [link para descargar el instalador o instalar Yarn](https://yarnpkg.com/es-ES/docs/install)

```bash
# Instala las dependencias
yarn install
```

---

## Comandos del boilerplate

| Comandos | Descripción |
| --- | --- |
| `yarn scss` | Observa la compilación de Scss. |
| `yarn pug` | Observa la compilación de Pug. |
| `yarn babel` | Observa la compilación de Babel. |
| `yarn browserify` | Ejecuta Browserify con soporte para Babel. |
| `yarn watchify` | Observa Browserify con soporte para Babel. |
| `yarn serve` | Levanta un servidor web live reload con Browser Sync. |
| `yarn proxy` | Levanta un servidor web proxy live reload con Browser Sync. |
| `yarn metalan` | Ejecuta en paralelo los scripts de **`sass`**, **`pug`** y **`watchify`**. |
| `yarn devserv` | Ejecuta en paralelo los scripts de **`metalangs`** y **`serve`**. |
| `yarn devprox` | Ejecuta en paralelo los scripts de **`metalangs`** y **`proxy`**. |
| `yarn imagemi` | Optimiza las imágenes .jpg y .png del proyecto. |
| `yarn webp` | Genera una versión .webp de todas las imágenes .jpg del proyecto. |
| `yarn svgmin` | Optimiza las imágenes .svg del proyecto. |
| `yarn gifmin` | Optimiza las imágenes .gif del proyecto. |
| `yarn jpgresize` | Redimensiona las imágenes .jpg del proyecto, requiere [ImageMagick](http://www.imagemagick.org) instalado para que funcione. |
| `yarn pngresize` | Redimensiona las imágenes .png del proyecto, requiere [ImageMagick](http://www.imagemagick.org) instalado para que funcione. |
| `yarn statics` | Mueve los archivos estáticos del proyecto. |
| `yarn assets` | Ejecuta de manera síncrona y bloqueante los comandos de **`statics`**, **`imagemin`**, **`webp`**, **`svgmin`** y **`gifmin`**. |
| `yarn clean` | Limpia el contenido de la carpeta public y crea los archivos y carpetas necesarios en ella. |
| `yarn min` | Minifica todos los archivos .html del proyecto. |
| `yarn min` | Minifica y ofusca el archivo **`script.js`** del proyecto. |
| `yarn uncss` | Remueve el código CSS innecesario del proyecto, tomando en cuenta la configuración del archivo **`uncss.json`**. |
| `yarn autoprefixer` | Ejecuta el autoprefijado CSS al archivo **`style.un.css`** que contiene el código CSS depurado del proyecto |
| `yarn min.css` | Minifica el código CSS del archivo **`style.un.css`** y lo guarda en **`style.css`**. |
| `yarn min` | Ejecuta de manera síncrona y bloqueante los comandos de **`min.html`**, **`min.js`**, **`uncss`**, **`autoprefixer`**, **`min.css`** y luego elimina el archivo **`style.un.css`**. |
| `yarn build` | Ejecuta de manera síncrona y bloqueante los comandos de **`assets`**, **`min`** y **`serve`**, éste comando prepara la versión de publicación del proyecto.  |
| `yarn start` | Ejecuta el comando **`devserve`**, éste comando inicia nuestro entorno de desarrollo para comenzar a trabajar en nuestro proyecto. |
