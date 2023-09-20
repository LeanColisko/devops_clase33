# Clase 32 - Ejercicio conteiners.

Objetivo: poner en practica lo que vimos sobre contruccion y operacion de contenedores.

## 1. Ejercicio

Crear un contenedor con la imagen de apache copiar el archivo index.html a la carpeta de trabajo y hacer que el contenedor escuche en el puerto 8080.

Luego de obtener la imagen hacer una prueba y verificar que el contenedor esta funcionando correctamente y muestre la pagina de apache.

Entregables:

- Dockerfile
- Pushear la imagen a DockerHub

## 2. Ejercicio

Nuestro equipo creo una API REST en `python3.8` y desean poder tener una imagen para correrla como contenedor.

Durante el Sprint Planning nos asignaron la tarea de escribir el Dockerfile para poder construir la imagen y así poder ejecutarla en los distintos entornos.

La API esta escrita en python, utiliza el framework Flask y atiende en puerto `6000`.

El equipo nos paso estas instrucciones para correr la aplicacion de forma local.

1. Clonar el repositorio

```bash
git clone http://gitlab.com/.../api-rest-python
```

2. Instalar las dependencias

```bash
pip install -r requirements.txt
```

3. Ejecutar la aplicacion

```bash
python app.py
```
4. Probar la aplicacion

```bash
curl http://localhost:6000
```

Entregables:

- Dockerfile
- Pushear la imagen a DockerHub
- Comandos para correr la imagen