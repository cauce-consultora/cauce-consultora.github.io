# cauce-consultora.github.io
Sitio web de Cauce Consultora

Sitio del trabajo grupal de la materia **Actuación Profesional del Licenciado en Sistemas de Información (APLSI)**. Presenta a Cauce, una consultora en sistemas de información, y su caso de consultoría con Orann, una empresa familiar de alimentos naturales.

Publicado en: https://cauce-consultora.github.io

## Estructura

| Archivo | Contenido |
|---|---|
| `index.html` | Inicio: propósito, desafíos que abordamos, servicios, metodología, principios, quiénes somos y caso destacado |
| `orann.html` | El proyecto Orann etapa por etapa, con un entregable por etapa |
| `img/logo-cauce.png` y `img/favicon.png` | Logo de la marca e ícono de la pestaña |
| `img/equipo/` | Fotos de los integrantes |

Es un sitio estático (HTML y CSS, sin dependencias).

## Cómo se publica

- **`cauce-web` (privado)** es donde se edita la web. Ahí está `orann.html` original, sin cifrar.
- **`cauce-consultora.github.io` (público)** es lo que publica GitHub Pages. Tiene la misma web, pero con `orann.html` **cifrado** con [StatiCrypt](https://github.com/robinmoisson/staticrypt): el proyecto solo se puede leer con la clave.
- En el repositorio público no se edita a mano el contenido: se suben ahí las versiones listas para publicar.

### Publicar un cambio

1. Subir el cambio a `cauce-web`, como siempre.
2. Si cambió `orann.html`: cifrar el original con StatiCrypt (la página web de StatiCrypt, en el navegador) usando la clave del proyecto, y subir el archivo cifrado al repositorio público con el nombre `orann.html`, reemplazando el anterior.
3. Si cambiaron otros archivos (`index.html`, imágenes, este README): subirlos también al repositorio público, tal cual.
4. **Nunca subir el `orann.html` sin cifrar al repositorio público.**

GitHub Pages publica el cambio en uno o dos minutos.

## Paleta de la marca

| Color | HEX |
|---|---|
| Azul Marino Profundo | `#2A2F3B` |
| Melocotón Suave | `#E89E8D` |
| Frambuesa | `#B64F6B` |
| Azul Marino Medianoche | `#141822` |
| Melocotón Coral | `#F4A78A` |

## Equipo

| Integrante | Rol |
|---|---|
| Paloma Steinberg | Product Owner |
| Camila Blanco | Scrum Master |
| Camila Albornoz | Consultora |
| Matías Fretes | Consultor |
| Juliana González | Consultora |
| Luis Santalla | Consultor |
