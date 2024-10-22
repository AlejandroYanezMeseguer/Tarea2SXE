# Tarea2SXE

### En esta tarea se realizaran una serie de tareas especificadas a continuacion con los respectivos pasos para hacerlas correctamente.

#### 1. Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo
  ‎ 
##### Para descargar la imagen debemos utilizar el siguiente comando:

```
sudo docker image pull alpine     #Copiar para descargar imagen de alpine
```
##### Para cmoprobar que esta instalada utilizaremos el siguiente comando:
```
sudo docker image ls     #Copiar para comprobar todas las imagenes instaladas en el equipo
```
#### 2. Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre
‎ 
##### Para crear un contenedor sin nombre debemos utilizar el siguiente comando:
```
sudo docker container create -i -t alpine     #Copiar para crear un contenedor sin nombre
```
##### Para cmoprobar que esta creadoutilizaremos el siguiente comando:
```
sudo docker ps -a     #Copiar para comprobar todos los contenedores creados y ver el nombre
```
##### Al crear el contenedor este se crea detenido, debemos iniciarlo con el siguente comando
```
sudo docker container start <nombre>     #Copiar para iniciar un contenedor de docker
```










