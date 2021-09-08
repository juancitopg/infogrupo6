**Sitio desarrollado por el Grupo 6 de la Comision 4 del Curso de Programacion Web del Informatorio 2021
**
_Primer proyecto proyecto del modulo de desarollo web_
_Usando template base: https://getbootstrap.com/docs/5.1/examples/cover/
**
**
_Proyecto del _
**
** Comenzando 
**
_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._
**
```
https://github.com/juancitopg/infogrupo6.git
```
**
** Pre-requisitos 📋
**
_Instalar las dependendencias del proyecto (ir a la carpeta de requirements)_
*
```
pip install -r base.txt
```
*
_Crear settings local.py_
*
from .base import *
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql', # Conector de DB
        'NAME': 'NombreBaseDeDatos',
        'USER': 'UsuarioBaseDeDatos',
        'PASSWORD': 'ContraseñaBaseDeDatos',
        'HOST': 'localhost',
        'PORT': '5432'
    }
}
```
*Importar los datos en la Base de Datos_
*
_Para probar el proyecto se deben cargar las preguntas, esto se puede realizar cargando el archivo **basededatosg6.json** por CMD (que incluye la Base de Datos completa con preguntas y usuarios de prueba) o tambien el archivo basededg6 (contiene las preguntas) desde el gestor de Base de Datos. Ambos archivos se encuentran en la carpeta **_docs_** del Proyecto._
*
** Construido con 
*
· [Django]Framework web
· [PostgreSQL]Base de datos
*
*
** Autor
·juan ignacio perez galan [juancitopg]
·Cowper-Coles, Francisco [cuperx]
