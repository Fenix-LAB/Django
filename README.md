## Repositorio del primer proyecto en de Django 
Para instalar el modulo es el siguiente comando:
```bash
pip install django
```

Para crear un proyecto, django ofrece el siguiente comando que creara una estructura de archivos muy utiles para desarrollar un proyecto:
```bash
django-admin startproject {name project} .
```

Para levantar un servidor de desarrollo, podemos usar el script de manage.py con el siguiente argumento:
```bash
python manage.py runserver
```

Para crear aplicaciones (Funcionalidades) del proyecto se utiliza el siguiente comando:
```bash
python manage.py startapp {name app}
```

Migraciones para base de datos:
```bash
python manage.py makemigrations
```

Ejecucion de migraciones:
```bash
python manage.py migrate
```

Django Shell:
```bash
python manage.py shell
```