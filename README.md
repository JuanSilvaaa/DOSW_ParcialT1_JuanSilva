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