## Laboratorio Módulo 14

Fichero de Instrucciones: Instructions\20486D_MOD014_LAK.md

Entregar el url de GitHub con la solución y un readme con las siguiente información:

1. **Nombres y apellidos:** Juan José Salvador Román
2. **Fecha:** 17/12/2020
3. **Resumen del Ejercicio:** 

Laboratorio: Implementación de API web

Se le ha pedido que cree una aplicación de restaurante basada en la web para los clientes de su organización. Para hacer esto, necesita crear una página que muestre todas las sucursales de restaurantes, permitir a los usuarios solicitar una reserva para una sucursal de restaurante seleccionada, agregar una página de anuncios deseados y permitir enviar una solicitud para un trabajo seleccionado.

Creará una aplicación de API web del lado del servidor y una aplicación ASP.NET Core MVC del lado del cliente. En la aplicación del lado del cliente, llamará a las acciones de la API web mediante HttpClient y jQuery.

Objetivos
Después de completar esta práctica de laboratorio, podrá:

- Agregue acciones a una aplicación de API web.

- Llame a las acciones de la API web mediante HttpClient.

- Llame a las acciones de la API web mediante jQuery.

**Ejercicio 1:**
agregar acciones y llamarlas mediante Microsoft Edge

En este ejercicio, primero agregará un controlador y una acción a una aplicación Web API. Luego, ejecutará la aplicación y verá el resultado con Microsoft Edge. Después de eso, agregará un controlador y una acción que obtiene un parámetro. Luego, ejecutará la aplicación y verá el resultado con Microsoft Edge. Finalmente, agregará una acción Publicar a la aplicación Web API.

Las principales tareas de este ejercicio son las siguientes:

1.Agregar un controlador y una acción a una aplicación de API web

2.Ejecutar la aplicación

3.Agrega un controlador y una acción que obtiene un parámetro

4.Ejecutar la aplicación

5.Agregar una acción Publicar a una aplicación API web


Para la publicación:
En Azure.hemos crado un recurso nuevo. Hemos puesto en la búsqueda app service + sql.
Esto nos abre la pantalla para crear plan app servicee + Service + Grupo Recurso + base de datos + servidor ..., todo
Una vez creado nos vamos al Visual Studio y publicamos. Cuando esté publicado

![subir_estos](C:\Users\Juanjo\Desktop\visualstudio_publish.PNG)

editamos y cambiamos 





![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)



**Ejercicio 2:**
llamar a una API web mediante código del lado del servidor

En este ejercicio, llamará a la API web que desarrolló en el ejercicio anterior utilizando la clase HttpClient. Para hacer esto, primero registrará el servicio IHttpClientFactory en el archivo Startup.cs. Luego, creará un controlador MVC y usará la clase HttpClient para llamar a una acción Get en la API web. Después de eso, creará otro controlador MVC y usará la clase HttpClient para llamar a una acción de publicación en la API web. Finalmente, agregará una acción al controlador MVC en la que usará la clase HttpClient para llamar a una acción Get en la API web que obtiene un parámetro.

Las principales tareas de este ejercicio son las siguientes:

1.Llamar a un método Get de API web

2.Ejecutar la aplicación

3.Llamar a un método de publicación de API web

4.Llamar a un método Get de API web que obtiene un parámetro

5.Ejecutar la aplicación


![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)




**Ejercicio 3:**
llamar a una API web mediante jQuery

En este ejercicio, llamará a una API web mediante jQuery. Primero creará un controlador MVC y usará jQuery para llamar a una acción Get en la API web. Después de eso, creará otro controlador MVC y usará jQuery para llamar a una acción Publicar en la API web.

Las principales tareas de este ejercicio son las siguientes:

1.Llamar a un método Get de API web mediante jQuery

2.Ejecutar la aplicación

3.Llamar a un método Get de API web mediante HttpClient

4.Llamar a un método de publicación de API web mediante jQuery

5.Ejecutar la aplicación

![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)


Hemos cambiado código para que coja las imagenes de local y si no hay pues del BlobStorage