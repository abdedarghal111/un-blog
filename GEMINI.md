## Comportamiento de gémini

- Hacer un commit después de cada cambio importante
- Revisar el fichero antes de planificar o tomar acciones
- En caso de dudar, preguntarme cualquier duda, eres un asistente o copiloto no una solución

## Resumen del Proyecto

Este proyecto es un blog personal para el canal de youtube Soy Abderra hecho en astro.

Sus características principales son:
- Toda la página está hecha en astro
- Enfocada para ser una página completamente estática
- Buen SEO
- Intuitiva
- Responsive
- Cómoda para los usuarios
- Fácil de navegar y leer
- Con información útil y explicaciones sencillas para todos los públicos

## Tecnologías Utilizadas

(Requerido) Enumera los principales lenguajes, frameworks, bibliotecas y herramientas utilizadas en este proyecto. Esto ayuda a Gemini a proporcionar código idiomático y a utilizar las herramientas correctas.

- **Framework:** Astro
- **Lenguaje:** TypeScript, JavaScript
- **Estilos:** CSS
- **Despliegue:** Nginx
- **Gestor de Paquetes:** pnpm

## Convenciones del Proyecto

- Usa camellCase
- Commits convencionales, atómicos y explicación breve (una sola frase)
- Comentarios solo cuando sean estrictamente necesarios
- Código autodescriptivo
- Optar por soluciones e implementaciones sencillas primero
- Sin tests (página estática sin funcionalidad)

## Archivos y Directorios Importantes

- `src/pages/`: Contiene las páginas principales del sitio (`.astro`).
- `src/components/`: Contiene componentes reutilizables de Astro.
- `src/layouts/`: Contiene las plantillas de página básicas, como `BaseLayout.astro`.
- `src/content/`: Contiene los archivos de contenido en formato Markdown o MDX.
    - `src/content/blog/`: Almacena las entradas del blog.
    - `src/content/roadmap.mdx`: Define la hoja de ruta del proyecto.
- `src/styles/`: Contiene los estilos globales CSS.
- `public/`: Contiene los activos estáticos como imágenes, fuentes y `robots.txt`.
- `astro.config.mjs`: El archivo principal de configuración de Astro.
- `package.json`: Define las dependencias y los scripts del proyecto.
- `tsconfig.json`: Archivo de configuración de TypeScript.

## Objetivos y Hoja de Ruta

Todos los objetivos del proyecto están ubicados en la lista en `content/roadmap.mdx`