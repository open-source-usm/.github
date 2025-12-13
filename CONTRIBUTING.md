# Contributing

## 1. Flujo de Trabajo (Workflow)

Utilizamos el modelo de colaboración [**Fork & Pull**](https://stackoverflow.com/questions/11582995/what-is-the-fork-pull-model-in-github). No se permiten commits directos a la rama `main` o `master` bajo ninguna circunstancia.

1.  **Fork:** Realice un fork del repositorio objetivo a su cuenta personal.
2.  **Rama (Branch):** Cree una rama descriptiva para su trabajo. Utilizaremos nombres de ramas semanticas, esto significa que el nombre debe reflejar el tipo de cambio que se realizará. [Mas información.](https://dev.to/marmariadev/estrategias-de-nomenclatura-para-ramas-en-git-mejorando-la-gestion-de-proyectos-de-software-3efa)

    - Formato: `tipo/nombre-corto`
    - Ejemplo: `feat/autenticacion-oauth`, `fix/fuga-memoria-api`.

3.  **Desarrollo:** Implemente los cambios localmente.
4.  **Sincronización:** Asegúrese de que su rama esté actualizada con `upstream/main` antes de enviar cambios para evitar conflictos.
5.  **Pull Request:** Envíe un Pull Request (PR) hacia la rama main del repositorio original.

## 2. Política de Commits

Adherimos a la especificación [**Conventional Commits**](https://www.conventionalcommits.org/) para mantener un historial de cambios claro y estructurado.

La estructura del mensaje debe ser: `<tipo>: <descripción breve>`

**Tipos permitidos:**

- `feat`: Una nueva funcionalidad para el usuario.
- `fix`: Corrección de un error (bug).
- `refactor`: Cambio de código que no corrige errores ni añade funcionalidades (mejora de estructura/rendimiento).
- `docs`: Cambios exclusivamente en la documentación.
- `chore`: Tareas de mantenimiento, dependencias o configuración de build.
- `test`: Añadir o corregir pruebas.

> **_NOTE:_** Si tiene dudas sobre qué tipo utilizar, opte por `chore`.

_Ejemplo correcto:_ `feat: implementar endpoint de login con JWT`, `fix: corregir validación de email en formulario de registro`
_Ejemplo incorrecto:_ `arreglé el bug del login`, `cambios en la documentación`

## 4. Reporte de Incidentes (Issues)

Antes de abrir un issue, verifique que no exista uno similar abierto o cerrado.

- **Bug Reports:** Debe incluir pasos exactos de reproducción, entorno (SO, versión del lenguaje/framework) y logs de error si aplica.
- **Feature Requests:** Debe detallar la justificación técnica o funcional de la propuesta.

## 5. Proceso de Revisión (Code Review)

Todos los Pull Requests requieren la aprobación de al menos un mantenedor del proyecto.

- Sea receptivo a los comentarios durante la revisión de código.
- Si se solicitan cambios, realícelos en la misma rama y haga push; el PR se actualizará automáticamente.

---

**Nota:** Al participar en este proyecto, usted acepta cumplir con nuestro [Código de Conducta](CODE_OF_CONDUCT.md). El incumplimiento de estas normas puede resultar en la desestimación de sus contribuciones.
