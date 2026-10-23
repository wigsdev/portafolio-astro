# Portafolio personal

Repositorio: [github.com/wigsdev/portafolio-astro](https://github.com/wigsdev/portafolio-astro)

```sh
pnpm create astro@latest -- --template minimal
```
## 🚀 Estructura del proyecto

Dentro del proyecto Astro encontrarás las siguientes carpetas y archivos:

```text
/
├── public/
│   ├── blog.jpg
│   ├── cv.pdf
│   ├── favicon.ico
│   ├── favicon.svg
│   ├── markdown-to-pdf.png
│   └── pomodoro.jpg
├── src/
│   └── pages/
│       ├── contacto.astro
│       ├── index.astro
│       ├── proyectos.astro
│       └── sobre-mi.astro
├── astro.config.mjs
├── package.json
├── pnpm-lock.yaml
├── README.md
└── tsconfig.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se publica en una ruta que se determina a partir del nombre del archivo.

Puedes colocar recursos estáticos, como imágenes, en el directorio `public/`.

## 🧞 Comandos

Ejecuta todos los comandos desde una terminal abierta en la raíz del proyecto:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Instala las dependencias del proyecto.           |
| `pnpm run dev`             | Inicia el servidor de desarrollo en `localhost:4321`. |
| `pnpm run build`           | Compila el sitio para producción en `./dist/`.   |
| `pnpm run preview`         | Muestra localmente la compilación antes de publicarla. |
