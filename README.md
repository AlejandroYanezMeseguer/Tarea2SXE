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
#### 3. Crea un contenedor con el nombre 'dam_alp1'. ¿Como puedes acceder a él?
‎ 
##### Para crear un contenedor el nombre dam_alp1 debemos utilizar el siguiente comando
```
sudo docker container create -i -t --name dam_alp1 alpine     #Copiar para crear un contenedor llamado dam_alp1
                                                              #Cambiar "dam_alp1" e caso de querer un contedor con otro nombre
```
##### Como se indico anteriormente los contenedores se crean detenidos, pero esta vez el comando para iniciarlo sera un poco diferente ya que lo encenderemos y accederemos a el con el siguiente comando
```
sudo docker container start --attach -i dam_alp1    #Copiar para iniciar y acceder al contenedot dam_alp1
                                                    #Cambiar "dam_alp1" en caso de acceder y iniciar otro contenedor
```
#### 4. Comprueba que ip tiene y si puedes hacer un ping a google.com
‎ 
##### Para comprobar la ip debemos acceder a el como anteriormente y utilizar el siguiente comando
```
ip a    #Copiar para mostrar la ip
```
##### A continuacion debemos hacer un ping a google, para ello utilizaremos el siguoiente comando
```
ping google.com     #Copiar para hacer ping a google
```










