# TO-DO-APP-DJANGO

BY: Diego Arteaga

## DESCRIPCION:
Bienvenido a To Do App, una aplicación de gestión de tareas desarrollada con Django. Este proyecto tiene como objetivo proporcionar a los usuarios una herramienta sencilla y eficaz para organizar sus actividades diarias. Con un diseño minimalista y responsivo, To Do App garantiza una experiencia de usuario fluida gracias a la concepción de su diseño.

### To Do App presenta las siguientes funcionalidades:

Formulario de registro: Los usuarios pueden crear cuentas personalizadas para gestionar sus tareas de manera segura y privada. El proceso de registro es sencillo e intuitivo.
Inicio de Sesión: Accede a tu cuenta de manera rápida y segura. La autenticación de usuarios garantiza que solo tú puedas ver y gestionar tus tareas.
Gestión de Tareas: Añade, edita y elimina tareas con facilidad. Organiza tus tareas por prioridad y fecha de vencimiento para mantenerte al día con tus responsabilidades.

## Instrucciones para Configurar y Ejecutar el Proyecto en Visual Studio Code
Paso 1: Clonar el Repositorio
Abre Visual Studio Code.
Abre una terminal integrada en VSCode (Ctrl + `).
Clona el repositorio desde GitHub:

![inicio de sesion](https://github.com/DieGoArt30/TO-DO-APP-DJANGO1/assets/149025522/dd5c7c3f-2681-41d0-9a10-42ff6faf6801)

![lista de tarea](https://github.com/DieGoArt30/TO-DO-APP-DJANGO1/assets/149025522/12f6aa32-e4e6-477b-8d5f-2e33519c4049)


## Estructura del Proyecto

![directorio](https://github.com/DieGoArt30/TO-DO-APP-DJANGO1/assets/149025522/70355154-43ec-4e74-899e-4c27500bfb51)

## Requisitos
- asgiref==3.8.1
- Django==5.0.6
- sqlparse==0.5.0
- tzdata==2024.1

## Instrucciones para Configurar y Ejecutar el Proyecto en Visual Studio Code

## Paso 1: Clonar el Repositorio
- Abre Visual Studio Code.
- Abre una terminal integrada en VSCode (Ctrl + `).
- Clona el repositorio desde GitHub:
git clone https://github.com/DieGoArt30/TO-DO-APP-DJANGO1.git
cd todoproject

## Paso 2: Crear archivo README.md
Asegúrate de que tu README.md contenga instrucciones claras para la configuración y ejecución del proyecto.

## Paso 3: Crear y Activar un Entorno Virtual
En la terminal integrada de VSCode, crea un entorno virtual:
python -m venv todoproject
todoproject\Scripts\activate

## Paso 4: Instalar Django
pip install django

## Paso 5: Instalar las dependencias
pip freeze > requirements.txt

## Paso 6: Crear un superusuario
python manage.py createsuperuser

## Paso 7: Ejecutar el servidor de desarrollo
python manage.py runserver
Ahora puedes acceder al proyecto en http://127.0.0.1:8000.

## Descripción de la Estructura del Proyecto
### Directorios y Archivos Principales
todoproject/: Contiene la configuración principal del proyecto.
settings.py: Configuraciones del proyecto Django.
urls.py: Configuración de las URL principales.
tasks/: Aplicación de gestión de tareas.
models.py: Define el modelo Task.
views.py: Contiene las vistas para listar, crear, editar y eliminar tareas.
urls.py: Configuración de las URL específicas de la aplicación de tareas.
forms.py: Define el formulario TaskForm.
templates/tasks/: Contiene las plantillas HTML para las vistas.

## Decisiones de Diseño Importantes
### Estructura del Modelo:
El modelo Task incluye campos para el título, descripción, fecha de creación, estado (pendiente o completado) y el usuario propietario de la tarea.

## Autenticación y Autorización:
Se utiliza el sistema de autenticación de Django para gestionar el acceso de los usuarios. Las vistas están protegidas con @login_required para asegurarse de que solo los usuarios autenticados puedan acceder a ellas.

## Interfaz de Usuario:
Se han utilizado iconos de Font Awesome para mejorar la interfaz de usuario, sustituyendo botones de texto por iconos intuitivos.

## Estilos y Diseño:
Se ha añadido una hoja de estilos CSS personalizada para mejorar la apariencia visual de la aplicación.

## Funcionalidad de Tareas:
- Los usuarios pueden crear, editar, eliminar y marcar tareas como completadas o pendientes.
- Las tareas completadas se muestran con una opacidad reducida para diferenciarlas visualmente.

## Mejoras y Adiciones Futuras:
- Integración con servicios de terceros para notificaciones.
- Implementación de recordatorios para las tareas.
- Mejora de la interfaz de usuario con más opciones de personalización.

## Contacto:
Para cualquier consulta o sugerencia, por favor contacta a Diego Aeteaga a traves de diehgohhz.30@gmail.com
