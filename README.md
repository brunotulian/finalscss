# 🦇 The Batcave Cafe

> Una experiencia de cafe inmersiva y unica inspirada en el universo de Gotham City.

Proyecto desarrollado como parte de la cursada de Desarrollo Web, aplicando diseño responsivo, maquetacion semantica, preprocesamiento con SCSS, librerias de animaciones y Bootstrap.

---

Enlace al Deploy
Puedes visualizar el proyecto funcionando en produccion aqui:
[Ver The Batcave Cafe en Netlify https://profound-cheesecake-130f87.netlify.app

---

Tecnologias y Herramientas Utilizadas
* **HTML5:** Maquetacion semantica y estructuracion de contenidos.
* **SCSS (Sass):** Estilos modulares organizados bajo la arquitectura 7-1 (variables, mixins, extend, partials).
* **Bootstrap 5:** Framework CSS para la estructuracion de componentes y la barra de navegacion responsiva.
* **AOS (Animate On Scroll):** Libreria externa para animaciones al hacer scroll.
* **CSS Animations:** Animaciones nativas mediante `@keyframes`.
* **Git y GitHub:** Control de versiones y despliegue continuo.

---

Estructura de Archivos
El proyecto sigue la estructura obligatoria solicitada:
```text
/
├── index.html            # Pagina de inicio
├── pages/                # Paginas secundarias
│   ├── nosotros.html
│   ├── menu.html
│   ├── salones.html
│   └── equipo.html
├── scss/                 # Archivos fuente de Sass (partials y main.scss)
│   ├── base/
│         ├── _base.scss
│         ├── _tipografia.scss
│   ├── components/
│         ├── _buttons.scss
│         ├── _cards.scss
│   ├── layout/
│         ├── footer.scss
│         ├── header.scss
│         ├── nav.scss
│   ├── utilities/
│         ├── mixins.scss
│         ├── variables.scss
│   └── main.scss
├── styles/               # CSS compilado
└── assets/               # Recursos multimedia (imagenes, logos, etc.)
