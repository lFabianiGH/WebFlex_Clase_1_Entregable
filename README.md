# Lucas' lair

Portafolio web personal desarrollado como proyecto del curso **Desarrollador Web Flex**.

## 🌐 Sitio web

**Sitio desplegado en GitHub Pages:**

https://lfabianigh.github.io/WebFlex_Clase_1_Entregable/

## 📌 Descripción

**Lucas' lair** es un sitio web personal orientado a compartir información sobre programación, tecnología y proyectos desarrollados de manera personal y colaborativa.

El sitio presenta información personal, una selección de proyectos y diferentes medios de contacto. Entre los proyectos presentados se encuentran **Ticketinhaber**, una plataforma para la gestión de tickets de soporte IT para dependencias de la administración pública municipal, y **Voterix**, una aplicación web para el control de votaciones en tiempo real. También se incluye una sección destinada a proyectos actualmente en desarrollo.

## 🎯 Objetivo

El proyecto tiene como objetivo desarrollar progresivamente un sitio web personal aplicando los conocimientos adquiridos durante el curso de Desarrollo Web, incorporando buenas prácticas de HTML, CSS, diseño responsive, Bootstrap y preprocesamiento mediante Sass/SCSS.

## 🧩 Secciones del sitio

El sitio está organizado en diferentes secciones y páginas:

* **Inicio:** presentación personal y descripción general.
* **Sobre mí:** información personal y profesional.
* **Proyectos:** presentación de proyectos personales y colaborativos.
* **Servicios:** información relacionada con conocimientos y servicios.
* **Contacto:** diferentes medios para establecer comunicación.

## 🛠️ Tecnologías utilizadas

### HTML5

Utilizado para construir la estructura semántica y el contenido de las diferentes páginas del sitio.

### CSS3

El CSS utilizado por el sitio es el resultado de la compilación de los archivos SCSS.

### Sass / SCSS

La hoja de estilos fue refactorizada utilizando una arquitectura basada en **partials**, variables, mixins, nesting y el operador `&`.

La estructura principal es:

```text
scss/
├── main.scss
├── utilities/
│   ├── _variables.scss
│   └── _mixins.scss
├── base/
│   ├── _base.scss
│   └── _tipografia.scss
├── layout/
│   ├── _header.scss
│   ├── _nav.scss
│   ├── _sections.scss
│   └── _footer.scss
└── components/
    ├── _cards.scss
    ├── _links.scss
    ├── _lists.scss
    └── _media.scss
```

`main.scss` funciona como único punto de entrada y utiliza `@use` para organizar los distintos módulos.

El resultado de la compilación se genera en:

```text
styles/
└── style.css
```

### Bootstrap

Se utiliza **Bootstrap 5** mediante CDN para determinados componentes y funcionalidades de la interfaz, integrándolo con los estilos propios del proyecto.

### Google Fonts

El proyecto utiliza fuentes externas mediante Google Fonts, incluyendo Montserrat, Inter, Playfair Display y Roboto Mono.

## 📱 Diseño responsive

El sitio incorpora diseño adaptable mediante **CSS Grid, Flexbox y media queries**, permitiendo reorganizar los contenidos según el tamaño de pantalla.

La navegación y las distintas secciones se adaptan a dispositivos de diferentes resoluciones.

## 📁 Estructura del proyecto

```text
WebFlex_Clase_1_Entregable/
├── assets/
│   └── img/
├── pages/
│   ├── contacto.html
│   ├── proyectos.html
│   ├── servicios.html
│   └── sobre-mi.html
├── scss/
│   ├── main.scss
│   ├── utilities/
│   ├── base/
│   ├── layout/
│   └── components/
├── styles/
│   └── style.css
├── index.html
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Compilación de SCSS

El proyecto utiliza Sass como dependencia de desarrollo.

Para compilar la hoja de estilos desde el directorio raíz:

```bash
npx sass --no-source-map scss/main.scss styles/style.css
```

El archivo CSS generado es un **resultado de compilación** y no constituye la fuente principal de los estilos.

## 👤 Autor

**Lucas Fabiani**

Analista de Sistemas y docente. El sitio funciona como espacio personal para compartir intereses relacionados con programación, tecnología y proyectos de desarrollo.

## 📬 Contacto

El sitio dispone de diferentes medios de contacto, incluyendo correo electrónico y redes sociales.

Para conocer los medios disponibles, consultar la sección **Contacto** del sitio.

## 📄 Licencia

Proyecto desarrollado con fines educativos y como parte del proceso de aprendizaje del curso **Desarrollador Web Flex**.
