# LAENN Digital

Sitio web institucional de LAENN Digital. El proyecto presenta los servicios de desarrollo web, marketing digital, gestión de redes sociales y creación de contenido visual.

## Tecnologías
- HTML5
- CSS3
- JavaScript
- Git y GitHub
- GitHub Actions
- GitHub Pages

## Estructura
```text
laenn-digital/
├── .github/workflows/deploy.yml
├── css/styles.css
├── js/script.js
├── index.html
├── README.md
└── .gitignore
```

## Ejecución local
Abre `index.html` en un navegador. Para una experiencia de desarrollo más cómoda, puedes usar la extensión Live Server de Visual Studio Code.

## Publicación automática (CI/CD)
El flujo de GitHub Actions se ejecuta cuando se realiza un `push` a la rama `main` o manualmente desde la pestaña Actions.

1. Obtiene el código del repositorio.
2. Comprueba que existan los archivos esenciales y las referencias CSS/JavaScript.
3. Prepara una carpeta `_site` con el HTML, CSS y JavaScript del sitio.
4. Publica el sitio cuando la validación termina correctamente.

## Activar GitHub Pages
En GitHub, entra en **Settings → Pages** y selecciona **GitHub Actions** como método de publicación. Después de subir el workflow a `main`, revisa la pestaña **Actions** para comprobar el resultado.

La dirección final tendrá normalmente este formato:
`https://TU-USUARIO.github.io/laenn-digital/`

Reemplaza `TU-USUARIO` por tu nombre de usuario de GitHub.

## Actualizaciones
Cada vez que se suban cambios a `main`, GitHub Actions volverá a validar y publicar el sitio automáticamente.
