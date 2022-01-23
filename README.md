# La vida en tercera persona

Aquest paquet de python agafa la imatge de dues càmeres i les processa de tal manera que les reconstrueix adaptant-les al format de les ulleres Oculus Rift.

### Autors
Sergi Mallafré Virumbrales

## Dependències
* Python ~= 2.7
* Ubuntu 16
* ROS Kinetic

## Instal·lació
1. Clonar projecte a una carpeta
2. ```catkin init```
3. ```catkin_make```

## Ús 
1. Endollar les dues càmeres al portàtil
2. Assegurar-se que les càmeres són detectables (```ls /dev```apareix video0 i video1, també pot aparèixer video2, agafar el que es cregui convenient modificant el fitxer publish_stereo.launch)
3. Col·locar-se a la carpeta CamCapt (On l'hagis clonat)
4. ```source devel/setup.bash```
5. ```roslaunch openhmd_ros publish_stereo.launch```
