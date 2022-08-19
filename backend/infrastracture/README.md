## Practicas de codigo legible
 Indexacion correcta : 
 Es una buena idea manejar una indexacion consistente en nuestro codigo para un leido legible.
 Code grouping :
 Siempre es bueno separar las funciones por almenos 2 espacios de otras funciones que no tengan que ver con la anterior
 Commenting and doccumentation :
 Se debe evitar comentar cosas demasiado obvias y tratar de explicar el codigo de manecra correcta 
 Avoid Deep Nesting 
 Se debe evitar hacer saltos de linea e indexacion para cada for / if esto crearia un codigo muy pesado
 Consistent Temporary Names : 
 Es bueno mantener nombres largos para variables que usaremos pero esto no aplica para las variables temporales que deben ser de los menores caracteres que se pueda
 ![image](https://user-images.githubusercontent.com/82822546/185634100-ceb4c2f8-bc4c-4e6b-bc79-18df569cc32a.png)

## Pipeline
Este estilo con programacion orientado a objetos es usado en las clases de backend/models ya que estas clases contienen funciones que retornan datos que no son compartidos entre otras funciones de la misma clase.
## Persistent Tables
Los archivos de repositorio de la parte de infraestructura utilizan el estilo de programacion de persistent tables ya que al establecer una conexion directa con la base de datos asociada, cuentan con lineas de queries para la extraccion y modificacion de la Base de Datos.
![image](https://user-images.githubusercontent.com/82822546/185633813-dcf47291-f8a6-4a09-870a-fc84edbabdeb.png)



