# Sistema de Gestión Empresarial

## Descripción del proyecto

Este proyecto es un sistema web integral para "Bootcamp Coders", enfocado en la gestión de estudiantes, relatores y cursos para sus programas de transformación digital. Como parte de un equipo multidisciplinario, mi rol es desarrollar una solución Fullstack robusta y escalable.

Las tecnologías y herramientas ocupadas son las siguientes:
- Python
- Django
- PostgreSQL
- Bootstrap

## Consideraciones

-  El sistema debe permitir registrar nuevos participantes.
-  Se debe crear una vista para que los participantes puedan iniciar sesión con su correo y contraseña.
-  Luego de iniciar la sesión, los participantes deberán poder modificar sus datos, exceptuando el correo electrónico y su foto. Esta vista esta protegida con csrf_token y los datos que se utilicen en la plantilla son extraídos del token.
-  La vista del administrador debe mostrar los participantes registrados y permitir aprobarlos para cambiar su estado.

## Instalación 🚀

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

### Pre-requisitos 📋

Que cosas necesitas para instalar el software.

```
Visual Studio Code, Node, Git, Github
```

### Instalación 🔧
Realizar un fork o clon del proyecto.
Importar proyecto al IDE de preferencia para ejecutar.
Para ejecutar en consola realizar el build (empaquetado) de la aplicación.

```bash
git clone https://github.com/VictorPenafiel/Django_Academia.git
cd proyecto
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Construido con 🛠️

* [Python](https://www.python.org/django)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)

## Contribuye 🖇️

```bash
# Fork → Crea rama → Cambios → Commit → Pull Request
```

## Autores ✒️

https://github.com/victorpenafiel

## Licencia 📄

Ningún Derecho Reservado.  [Creative Commons Atribución/Reconocimiento 4.0 ](https://creativecommons.org/licenses/by/4.0/deed.es).

Este proyecto está bajo la Licencia - mira el archivo [LICENSE.md](LICENSE.md) para detalles