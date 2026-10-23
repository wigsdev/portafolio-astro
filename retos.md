# Retos de Astro

## Reto 1 de 3: Mi primer sitio Astro

**Objetivo:** Crear y publicar en GitHub un mini portafolio de cuatro páginas sin enviar JavaScript al navegador.

### Requisitos

1. [x] Crear el proyecto `portafolio-astro` con la plantilla mínima.
2. [x] Crear las páginas Inicio, Sobre mí, Proyectos y Contacto, y enlazarlas entre sí.
3. [x] Definir en `proyectos.astro` un arreglo de tres proyectos con nombre y descripción, y mostrarlos con `map()`.
4. [x] Guardar el CV en PDF dentro de `public/` y enlazarlo desde Sobre mí.
5. [x] Añadir `alt` a todas las imágenes y comprobar que no haya avisos en Audit.
6. [x] Ejecutar la compilación y comprobar que `dist/` no contenga archivos `.js`.

### Entregable

- [x] Publicar el repositorio en GitHub con al menos cuatro commits.
- [x] Añadir un `README.md` con los comandos del proyecto.

## Reto 2 de 3: Informe de arquitectura

**Objetivo:** Analizar tres sitios reales con la mirada de Astro: islas, directivas y modo de renderizado.

### Requisitos

1. [x] Elegir tres sitios distintos: un blog o periódico, una tienda en línea y una aplicación (por ejemplo, Gmail).
2. [x] Tomar una captura de cada sitio y marcar sus islas, como en el diagrama de clase.
3. [x] Proponer y justificar para cada isla una directiva `client:*` o `server:defer`.
4. [x] Clasificar tres páginas de cada sitio como estáticas o bajo demanda.
5. [x] Indicar si se construiría cada sitio con Astro y explicar por qué.

### Entregable

- [x] Preparar un PDF de dos a cuatro páginas con las capturas anotadas y una tabla resumen por sitio.

## Reto 3 de 3: Explorador del CLI

**Objetivo:** Dominar los comandos de Astro y documentarlos como guía para compañeros.

### Requisitos

1. [x] Iniciar el servidor en el puerto `3000` con apertura automática del navegador.
2. [x] Usar `--host` y abrir el sitio desde un celular conectado a la misma red Wi-Fi.
3. [x] Ejecutar `npx astro info` y explicar cada línea del resultado.
4. [x] Probar `npx astro dev --background` y los comandos `status`, `logs` y `stop`.
5. [x] Provocar un error de compilación por una etiqueta sin cerrar, copiar el mensaje y corregirlo.

### Entregable

- [x] Añadir al `README.md` del Reto 1 una sección «Guía del CLI» con cada comando, su propósito y una captura.
