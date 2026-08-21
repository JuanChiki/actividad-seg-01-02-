# Seguimiento 01 - Actividad SEG-01

## Descripción

Este repositorio corresponde al Seguimiento 01 de la asignatura de Programación Web. El proyecto consiste en un sitio web sencillo de tres páginas HTML sobre una cafetería llamada **Pixel Café**.

La actividad tiene como objetivo practicar el trabajo colaborativo con Git y GitHub mediante commits, ramas, Pull Requests, revisión de cambios, resolución de conflictos y etiquetas.

## Integrantes

| Integrante                 | Usuario de GitHub | Equipo |                  Qué hizo                 |              Commits            |
| -------------------------- | ----------------- | ------ | ----------------------------------------- | ------------------------------- |
| Ana Isabel Patiño Carvajal | @Ana-Isabel04     | 02     | creo y añadio Servicios y bitacora-git.md | f0a2f0e,7f9d008,39289ed,51f825f |
| Michael Giraldo Restrepo   | @MichaelGiraldoR  | 02     | creo y añadio Contactos y .gitignore      | b17e3b5,2fa23d3,965602e,f05ac20 |
| Juan David Rojas Villegas  | @JuanChiki        | 02     | creo y añadio index y el readme           | ad18260,369a288,5c4af67,d2b406c |

## Contenido del proyecto

El sitio web está compuesto por tres páginas HTML:

* `index.html` — Página principal de Pixel Café.
* `servicios.html` — Lista de servicios ofrecidos por la cafetería.
* `contacto.html` — Información de contacto ficticia.

Las tres páginas están conectadas mediante un menú de navegación.

## Tecnologías utilizadas

* HTML5
* Git
* GitHub

## Flujo de trabajo con Git

El proyecto se desarrolló mediante un flujo de trabajo colaborativo utilizando ramas `feature/<algo>`.

La rama `main` se encuentra protegida para evitar cambios directos. Cada integrante trabaja en su propia rama, realiza sus commits y posteriormente abre un Pull Request hacia `main`.

Cada Pull Request es revisado por el otro integrante antes de realizar la fusión.

El flujo utilizado es:

```text
Rama feature
     │
     ▼
   Commits
     │
     ▼
Push al repositorio
     │
     ▼
Pull Request
     │
     ▼
Revisión del otro integrante
     │
     ▼
Merge a main
```

Ningún integrante fusiona su propio Pull Request.

## Ramas del proyecto

Las ramas utilizadas para desarrollar las funcionalidades son:

* `feature/index` — Desarrollo de la página principal.
* `feature/servicios` — Desarrollo de la página de servicios.

La página de contacto se integra como parte del desarrollo colaborativo del proyecto.

## Commits

Cada integrante realiza como mínimo cuatro commits en momentos diferentes.

Los mensajes de commit utilizan prefijos de tipo para identificar el propósito de cada cambio:

* `feat:` — Nuevas funcionalidades.
* `fix:` — Correcciones.
* `docs:` — Cambios relacionados con documentación.

El objetivo es mantener un historial de Git claro y organizado.

## Pull Requests y revisión

Cada integrante abre un Pull Request para integrar sus cambios a `main`.

El otro integrante revisa el Pull Request desde la pestaña **Files changed**, dejando al menos un comentario relacionado con los cambios realizados.

Después de la revisión correspondiente, el Pull Request es fusionado por el integrante que realizó la revisión.

## Resolución de conflicto

Como parte de la actividad se provoca intencionalmente un conflicto en el archivo `index.html`, específicamente en la sección correspondiente al menú de navegación.

Los integrantes realizan cambios diferentes sobre la misma línea desde sus respectivas ramas. Posteriormente se resuelve el conflicto de manera colaborativa.

El registro detallado del conflicto se encuentra en:

```text
docs/bitacora-git.md
```

La bitácora contiene:

* Archivo y línea donde ocurrió el conflicto.
* Contenido de cada versión.
* Criterio utilizado para resolverlo.
* Hash del commit de fusión.

## .gitignore

El proyecto incluye un archivo `.gitignore` para evitar que archivos y directorios que no deben formar parte del repositorio sean registrados por Git.

También se verifica su funcionamiento mediante la creación local del directorio `bin/`, comprobando que no sea incluido en el repositorio remoto.

## Etiqueta de versión

La versión final del proyecto se identifica mediante la etiqueta:

```text
v0.1.0
```

Esta etiqueta se publica en el repositorio remoto una vez finalizado el desarrollo y la integración de los cambios.

## Estructura del proyecto

```text
actividad-seg-01-02/
│
├── index.html
├── servicios.html
├── contacto.html
├── README.md
├── .gitignore
│
└── docs/
    └── bitacora-git.md
```

## Objetivos

* Practicar el uso de Git y GitHub.
* Trabajar con ramas independientes.
* Realizar commits pequeños y descriptivos.
* Utilizar Pull Requests.
* Realizar revisión cruzada entre integrantes.
* Resolver conflictos de Git.
* Utilizar correctamente `.gitignore`.
* Crear y publicar una etiqueta de versión.
* Mantener un historial de trabajo organizado.
