# PROBANDO DJANGO

## Índice
<a href="#1"> 1. Instalación Django</a><br>
<a href="#2"> 2. Archivos proyecto Django</a>

<div id="1">

## 1. Instalación Django
1. Instalar python desde [python.org](https://python.org)
2. Desde ahora siempre vamos a trabajar desde la consola
3. Luego verificar lo siguiente:
```py
python --version
pip --verison
```
4. Ahora vamos a crear nuestro entorno local:
```py
# CUALCQUIERA DE LAS DOS SIRVE
python -m venv NOMBRE_ENTORNO_LOCAL
py -m venv NOMBRE_ENTORNO_LOCAL
```
5. Activamos nuestro entorno local:
```py
# EN WINDWOS
NOMBRE_ENTORNO_LOCAL\Script\activate
# EN LINUX Y MC
source NOMBRE_ENTORNO_LOCAL\Script\activate
```
Te vas a dar cuenta que estamos trabajando bajo el entorno ya que se va anteponer (env) en la direccion que tengas en la consola
6. Instalar Django:
```py
pip install django -U
```
Ahora que tenemos instalado Django en nuestro entorno local, vamos a crear un proyecto
7. Creamos nuestro proyecto:
```py
# EL PUNTO ES PARA DECIRLE A DJANGO QUE NO QUEREMOS CREAR UNA CARPETA CON EL NOMBRE DEL PROYECTO, PUESTO QUE VAMOS A UTILIZAR LA CARPETA EN LA QUE ESTAMOS, EL . ES OPCIONAL
django-admin startproject NOMBRE_PROYECTO . 
```
Listo tenemos nuestro proyecto django instalado

</div>
<div id="2">

## 2. Archivos Proyecto Django
- **\_\_init\_\_.py** : Archivo vacio, su unico objetivo es declarar la carpeta como un módulo de python.
- **settings.py** : Uno de los archivos mas importantes del proyecto, puesto que defino las configuraciones de nuestro proyecto
- **urls.py** : Archivo principal, punto de entrada para todas las peticiones que lleguen al proyecto.
- **wsgi.py** : Archivo usado para el deployment, es la interfaz wsgi con nuestro proyecto cuando el servidor este correidno en produccion

</div>