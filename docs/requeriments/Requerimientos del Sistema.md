# 📄 Requerimientos del Sistema

## 1. Lista general de requerimientos

El sistema de Silabinfo tiene los siguientes requerimientos (descripción a alto nivel):

### 1.1 Requerimientos funcionales

El sistema de Silabinfo debe tener la capacidad de:

1. Realizar una solicitud de un espacio o equipo y determinar si se le puede brindar o no segun
el tipo de usuario.
2. Utilizar la informacion de las materias desde la plataforma enlace
3. Utilizar la informacion de los profesores desde recursos humanos


### 1.2 Requerimientos funcionales

El sistema de Silabinfo debe tener:

1. Tener los colores alusivos al programa de ingenieria de sistemas el cual es verde claro.
2. La aplicacion debe ser responsive y tener tipologia legible.


## 2. Diagramas de caso de uso




### 2.1 Requerimiento Funcional 1

| Campo | Descripción                                                                                                                                                                           |
|------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID** | RF-01                                                                                                                                                                                 |
| **Nombre del requerimiento** | Estudiante Solicita un equipo                                                                                                                                                         |
| **Descripción** | *El sistema debe recibir la solicitud del estudiante y decidir si se le puede dar o no un equipo*                                                                                     |
| **Precondiciones** | *Para que el sistema cumpla con este requerimiento, sislabinfo debe comprobar que es un <br> estudiante, tiempo de la reserva, <br> y si ya tiene una reserva*                        |
| **Actor** | *(Estudiante)*                                                                                                                                                                        |
| **Flujo principal** | 1. El actor estudiante solicita un equipo<br>2. El sistema silabinfo determina si se le puede o no dar la reserva al usuario<br>3. El sistema silabinfo da la respuesta al estudiante |
| **Diagrama de caso de uso** | *![Diagrama1](C:\Users\juan.silva-c\Desktop\DOSW_ParcialT1_JuanSilva\docs\images\CasoDeUso1.png)<br>imagen en la carpeta "images"*                                                    |
| **Poscondiciones** | *Se espera como resultado que despues de la solicitud el programa le reserve si es posible el uso del equipo al estudiante*                                                           |


### 2.2 Requerimiento Funcional 2

| Campo | Descripción                                                                                                                                       |
|------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **ID** | RF-02                                                                                                                                             |
| **Nombre del requerimiento** | Silabinfo Solicita informacion de materias a enlace                                                                                               |
| **Descripción** | *El sistema debe ir a la clase Enlace y solicitar la informacion  de las materias*                                                                |
| **Precondiciones** | *Para que el sistema cumpla con este requerimiento, Enlace debe tener <br> previamente la informacion de la materia en una sola cadena*           |
| **Actor** | *Silabinfo*                                                                                                                                       |
| **Flujo principal** | 1. El actor silabinfo pide la informacio<br>2. El sistema enlace recibe la solicitud<br>3. El sistema enlace da la informacion en una sola cadena |
| **Diagrama de caso de uso** | *![Diagrama2](C:\Users\juan.silva-c\Desktop\DOSW_ParcialT1_JuanSilva\docs\images\CasoDeUso2.png)<br/>imagen en la carpeta "images"*               |
| **Poscondiciones** | *Se espera como resultado que el sistema silabinfo reciba satisfactoriamente la informacion <br>de las materias*                                  |
