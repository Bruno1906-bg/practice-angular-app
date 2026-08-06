# Bruno Benitez — Portafolio Personal

Portafolio personal desarrollado con **Angular**, creado para presentar mi
perfil como desarrollador, las tecnologías con las que trabajo y los
proyectos en los que he participado. El sitio está construido con
**componentes standalone**, estilizado con CSS puro y pensado con una
estructura de secciones navegables mediante anclas.

🔗 Demo: <!-- agrega aquí el link una vez desplegado (Vercel / Netlify / GitHub Pages) -->

---

## Tecnologías utilizadas

- **Angular** (standalone components, sin NgModules)
- **TypeScript**
- **HTML5** semántico
- **CSS3** (Grid, Flexbox, variables, transiciones)
- **Angular CLI** 20.x

---

## Secciones del sitio

| Sección | Descripción |
|---|---|
| **Perfil** | Foto, nombre y descripción personal. |
| **Herramientas y Tecnologías** | Lenguajes, frameworks, bases de datos y otras herramientas, organizadas en tarjetas. |
| **Proyectos** | Tarjetas con logo, descripción, tags de tecnologías y links a demo/GitHub de cada proyecto. |
| **Contacto** | Información y enlaces de contacto. |

---

## Estructura del proyecto

```
src/
└── app/
    └── components/
        └── landing-page/
            ├── landing-page.html   # Estructura de las secciones del portafolio
            ├── landing-page.css    # Estilos del portafolio
            └── landing-page.ts     # Lógica del componente
public/
└── logoMigo.png                   # Assets estáticos servidos desde la raíz
```

---

## Cómo correr el proyecto localmente

Clona el repositorio e instala las dependencias:

```bash
git clone https://github.com/Bruno1906-bg/practice-angular-app.git
cd practice-angular-app
npm install
```

Levanta el servidor de desarrollo:

```bash
ng serve
```

Abre `http://localhost:4200/` en tu navegador. La app se recarga
automáticamente al modificar cualquier archivo fuente.

---

## Scaffolding de componentes

Para generar un nuevo componente:

```bash
ng generate component nombre-del-componente
```

Para ver todos los schematics disponibles (components, directives, pipes, etc.):

```bash
ng generate --help
```

---

## Build de producción

```bash
ng build
```

Los artefactos de build se generan en la carpeta `dist/`, optimizados por
defecto para rendimiento en producción.

---

## Pruebas

Pruebas unitarias con Karma:

```bash
ng test
```

Pruebas end-to-end (requiere configurar un framework, Angular CLI no incluye uno por defecto):

```bash
ng e2e
```

---

## Autor

**Bruno Benitez Gómez**
Estudiante de Técnico Superior Universitario en Desarrollo de Software
Multiplataforma — Universidad Tecnológica de la Riviera Maya.

- GitHub: [@Bruno1906-bg](https://github.com/Bruno1906-bg)
<!-- - LinkedIn: agrega tu link -->
<!-- - Correo: agrega tu correo -->

---

## Recursos adicionales

Para más información sobre Angular CLI, incluyendo referencia detallada de
comandos, visita [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli).
