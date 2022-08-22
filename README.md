
## SOLID PRACTICES
# Single Responsibility
Este principio tiene como objetivo separar los comportamientos para que, si surgen errores como resultado de su cambio, no afecten otros comportamientos no relacionados.
En este ejemplo vemos que esta clase se encarga solo de hacer las conexiones con la base de datos 
![image](https://user-images.githubusercontent.com/82822546/185997055-7e791c97-21d3-43d3-93a0-6d07d2882d2d.png)

# Open Closed
Este principio tiene como objetivo extender el comportamiento de una Clase sin cambiar el comportamiento existente de esa Clase. Esto es para evitar causar errores dondequiera que se use la Clase.
En este ejemplo la Clase Asistente que se conecta a la base de datos puede retorna un Asistente basado en el ID pero tambien podemos agregar otras funciones como GETALL , CREATE todo esto sin afectar el comportamiento que ya tiene.
![image](https://user-images.githubusercontent.com/82822546/185998627-05c33767-fb3b-436d-a56d-925c46e37b0d.png)
