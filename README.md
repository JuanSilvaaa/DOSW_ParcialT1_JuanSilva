# DOSW_ParcialT1_JuanSilva

## Punto1 - Diagrama de contexto

Diagrama de contexto con las solicitudes que pueden hacer los usuarios de tipo profesor, estudiante o monitor a la 
aplicacion

![Diagrama de clases](C:\Users\juan.silva-c\Desktop\DOSW_ParcialT1_JuanSilva\docs\images\DiagramaContexto.png)

## Punto2 - Tipos de patron de diseño

Podemos implementar los siguientes patrones de diseño:

1)
    a) Factory method
    b) Creacional
    c) Lo usariamos en el caso de Usuarios, tenemos una clase padre que se llamaria Usuarios 
       y tambien tendriamos a sus hijos que serian Profesor, Estudiante, Monitor.
2)
    a) Singleton
    b) Creacional
    c) Lo usariamos para asegurarnos de que cada solicitud tenga una unica instancia y que la solicitud de una 
       sala no pida una maquina o una oficina.

## Punto 3 - Requerimientos del sistema

### Funcionlaes (3)

# este cumple con el patron de diseño singleton al especificar que se solicita
1) Realizar una solicitud de un espacio o equipo y determinar si se le puede brindar o no segun 
   el tipo de usuario. 
2) Utilizar la informacion de las materias desde la plataforma enlace
3) Utilizar la informacion de los profesores desde recursos humanos

### No funcionales

1) Tener los colores alusivos al programa de ingenieria de sistemas el cual es verde claro.
2) La aplicacion debe ser responsive y tener tipologia legible.

## Punto 4 - Diagramas de casos de uso

caso de uso - Estudiante solicita equipo
historia:
Como Estudiante quiero solicitar un equipo para poder realizar mis trabajos

![imagen de solicitud](C:\Users\juan.silva-c\Desktop\DOSW_ParcialT1_JuanSilva\docs\images\CasoDeUso1.png)
----

caso de uso - Silabinfo Solicita informacion a enlace
historia:
Como Estudiante quiero solicitar un equipo para poder realizar mis trabajos a enlace para poder administrar mi sistema

![imagen de solicitud de informacion](C:\Users\juan.silva-c\Desktop\DOSW_ParcialT1_JuanSilva\docs\images\CasoDeUso2.png)

## Punto 5 - documento de requerimientos

Documento de requerimientos en la carpeta "requeriments"

## Punto 6 - descomposicion de tareas asociadas

- EPICA: Solicitud de reserva por un usuario
- HISTORIA DE USUARIO: Estudiante reserva un equipo en la plataforma de silabinfo
- TAREAS:
  - Front:
    - Realizar manual de identidad con los colores de la escuela y con bunea tipologia
    - Realizar los mockups de la interfaz grafica con el flujo
    - Programar en react los mockups
    - Desplegar
    - realizar conexion con back
  - Back:
    - Realizar diagramas de caso de uso
    - Realizar dragramas de clases
    - Realizar diagramas de secuencias 
    - Realizar pruebas 
    - Codificar el diagrama de clases con .java con el flujo de diagrama de secuencias y que funcionen las pruebas 
    - Conectar a base de datos 
    - Desplegar
    - Conectar a front