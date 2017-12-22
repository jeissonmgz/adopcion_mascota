# adopcion_mascota
Ejemplo en Django

Crear ambiente
----------------
python -m venv ambienteTest
cd ambienteTest
cd Scripts
activate #activar entorno
python -m pip install django #instalar Django
python -m pip freeze #Mostrar que se tiene instalado
python -m pip install psycopg2 #conector copn postgres
desactivate #desactivar entorno


Crear proyecto
----------------
django-admin.py startproject HelloWorld
manage.py migrate
manage.py createsuperuser (jeisson / 93o2o4o492o)
manage.py runserver

django-admin.py Linea de comandos de Django
--------------------------------------------
django-admin.py startproject nombre
django-admin.py startapp nombre
django-admin.py createsuperuser

manage.py empaquetador
------------------------
manage.py makemigrations #Crear migracion
manage.py migrate #Ejecutar migraciones
manage.py runserver #Correr el servidor



Adopcion de Mascotas
----------------------
django-admin.py startproject RefugioAnimal
#crear carpeta apps y entrar en ella por CMD
django-admin.py startapp mascota
agregar en settings.py en INSTALLED_APPS las apps creadas
manage.py makemigrations #Crear migracion a partir de las clases creadas
manage.py migrate #Modifica la base de datos
manage.py createsuperuser (jeisson / 93o2o4o492o)
manage.py runserver
manage.py shell
