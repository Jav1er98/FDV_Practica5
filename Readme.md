## Práctica 5: Waypoints.
## Objetivo: Realizar pruebas con el Sistema de Waypoints de Unity.

 - Importar el asset u obtenerlo en la asset store.
    - Iremos a la tienda de unity y descargaremos "Standard Assets (for Unity 2018.4)" del cual solo importaremos los siguientes archivos que nos interesan, en este caso serán los archivos Waypoint Progess Tracker y Waypoint Circuit.
    
    ![Paso 1](gifs/Captura5.png)
    
     - Seguido de esto colocaremos un suelo y un cubo al que seguir y para establercer el circutio usaremos unas esferas, creamos un Gameobject empty, en este pondremos las esferes como hijas suyas y le asignaremos el script de Waypoint Circuit y generará el circuito en base a como hemos colocado las esferas.
      
   ![Paso 2](gifs/Captura1.png)
   
   ![Paso 3](gifs/Captura2.png)  
   
   ![Paso 4](gifs/Captura3.png)  
    
   
 - Utiliza un personaje que realice el recorrido por un circuito que generes.
    - En este caso he asignado un esfera de color rojo que seguirá al cubo por el circuito, para ello asignamos a la esfera el script Waypoint Progress Tracker, el cual ajustaremos un par de parametros para dar una sensación más agil a la esfera, a este mismo el asignamos el script del circuito y como target el cubo. Finalmente añadimos otro script para que realice el movimiento la esfera al seguir al cubo (Follow.cs).
    
   ![Paso 5](gifs/Captura4.png)  
   
- El resultado es el siguiente:

   ![Paso 6](gifs/Ejercicio.gif)  
