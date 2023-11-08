# {{cookiecutter.project_name}}

## Español

{{cookiecutter.description_es}}

Este proyecto está estructurado y gestionado con Poetry para la gestión de dependencias y empaquetado. Incluye un `Makefile` para ejecutar tareas comunes de desarrollo.

## Características

- Gestión sencilla de dependencias con Poetry.
- Dependencias de desarrollo preconfiguradas para análisis de código y pruebas.
- `Makefile` para comandos abreviados fáciles de usar.

## Prerrequisitos

- Python {{cookiecutter.python_version}} o superior.
- Poetry para Python.

## Primeros Pasos

Para clonar el proyecto e instalar las dependencias, ejecute:

```bash
git clone https://github.com/tuusuario/{{cookiecutter.project_slug}}
cd {{cookiecutter.project_slug}}
make install
```

## Comandos del Makefile

- `make install`: Instala las dependencias del proyecto con Poetry.
- `make showdeps`: Muestra las dependencias actuales y sus últimas versiones disponibles.
- `make check`: Ejecuta controles de pre-commit en todos los archivos del proyecto.
- `make lint`: Realiza el linting del proyecto con flake8.
- `make sort`: Formatea las declaraciones de importación usando isort.
- `make mypy`: Ejecuta mypy para la verificación de tipos.
- `make test`: Ejecuta las pruebas con informes de cobertura.

Para obtener una lista completa de los comandos disponibles, ejecute `make help`.

## Flujo de Trabajo para el Desarrollo

- Para verificar y formatear el código antes de hacer commit:
  ```bash
  make check
  make sort
  make lint
  make mypy
  ```
  
- Para ejecutar pruebas:
  ```bash
  make test
  ```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, asegúrese de que todas las contribuciones sigan el siguiente flujo de trabajo:

1. Haga un fork del repositorio.
2. Cree una nueva rama para cada característica o mejora.
3. Envíe un pull request desde cada rama de características a la rama principal.

Tenga en cuenta que este proyecto está diseñado con fines educativos para un curso de ingeniería de pregrado.

## Licencia

Este proyecto está bajo la Licencia MIT - vea el archivo `LICENSE` para más detalles.

### Contacto

- Instructor: Guillermo Ibarra
- Correo Electrónico: guillermoibarra@gmail.com
- Repositorio del Proyecto: https://github.com/guillermoibarra/{{cookiecutter.project_slug}}

No dude en contactar si tiene alguna pregunta o sugerencia con respecto al curso o la plantilla del proyecto.

---

## English

{{cookiecutter.description}}

This template provides a structured Python project managed with Poetry for dependency management and packaging. It includes a `Makefile` for running common development tasks.

## Features

- Easy dependency management with Poetry.
- Pre-configured development dependencies for linting, type-checking, and testing.
- `Makefile` for easy-to-use command shortcuts.

## Prerequisites

- Python {{cookiecutter.python_version}} or higher.
- Poetry for Python.

## Getting Started

Clone the project and install the dependencies:

```bash
git clone https://github.com/guillermoibarra/{{cookiecutter.project_slug}}
cd {{cookiecutter.project_slug}}
make install
```

## Makefile Commands

- `make install`: Install project dependencies with Poetry.
- `make showdeps`: Display the current dependencies and their latest available versions.
- `make check`: Run pre-commit checks on all files in the project.
- `make lint`: Lint the project using flake8.
- `make sort`: Format the import statements using isort.
- `make mypy`: Run mypy for type checking.
- `make test`: Run tests with coverage reporting.

For a full list of available commands, run `make help`.

## Development Workflow

- To check and format code before committing:
  ```bash
  make check
  make sort
  make lint
  make mypy
  ```
  
- To run tests:
  ```bash
  make test
  ```

## Contributing

Contributions to this project are welcome. Please ensure that all contributions adhere to the following workflow:

1. Fork the repository.
2. Create a new branch for each feature or improvement.
3. Send a pull request from each feature branch to the main branch.

Please note that this project is designed for educational purposes in an undergraduate engineering course.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

- Instructor: Guillermo Ibarra
- Email: guillermoibarra@gmail.com
- Project Repository: https://github.com/guillermoibarra/{{cookiecutter.project_slug}}

Feel free to reach out if you have any questions or suggestions regarding the course or the project template.
