## Laboratorio M�dulo 14

Fichero de Instrucciones: Instructions\20486D_MOD014_LAK.md

Entregar el url de GitHub con la soluci�n y un readme con las siguiente informaci�n:

1. **Nombres y apellidos:** Juan Jos� Salvador Rom�n
2. **Fecha:** 17/12/2020
3. **Resumen del Ejercicio:** 

Laboratorio: Implementaci�n de API web

Se le ha pedido que cree una aplicaci�n de restaurante basada en la web para los clientes de su organizaci�n. Para hacer esto, necesita crear una p�gina que muestre todas las sucursales de restaurantes, permitir a los usuarios solicitar una reserva para una sucursal de restaurante seleccionada, agregar una p�gina de anuncios deseados y permitir enviar una solicitud para un trabajo seleccionado.

Crear� una aplicaci�n de API web del lado del servidor y una aplicaci�n ASP.NET Core MVC del lado del cliente. En la aplicaci�n del lado del cliente, llamar� a las acciones de la API web mediante HttpClient y jQuery.

Objetivos
Despu�s de completar esta pr�ctica de laboratorio, podr�:

- Agregue acciones a una aplicaci�n de API web.

- Llame a las acciones de la API web mediante HttpClient.

- Llame a las acciones de la API web mediante jQuery.

**Ejercicio 1:**
agregar acciones y llamarlas mediante Microsoft Edge

En este ejercicio, primero agregar� un controlador y una acci�n a una aplicaci�n Web API. Luego, ejecutar� la aplicaci�n y ver� el resultado con Microsoft Edge. Despu�s de eso, agregar� un controlador y una acci�n que obtiene un par�metro. Luego, ejecutar� la aplicaci�n y ver� el resultado con Microsoft Edge. Finalmente, agregar� una acci�n Publicar a la aplicaci�n Web API.

Las principales tareas de este ejercicio son las siguientes:

1.Agregar un controlador y una acci�n a una aplicaci�n de API web

2.Ejecutar la aplicaci�n

3.Agrega un controlador y una acci�n que obtiene un par�metro

4.Ejecutar la aplicaci�n

5.Agregar una acci�n Publicar a una aplicaci�n API web


Para la publicaci�n:
En Azure.hemos crado un recurso nuevo. Hemos puesto en la b�squeda app service + sql.
Esto nos abre la pantalla para crear plan app servicee + Service + Grupo Recurso + base de datos + servidor ..., todo
Una vez creado nos vamos al Visual Studio y publicamos. Cuando est� publicado

![subir_estos](C:\Users\Juanjo\Desktop\visualstudio_publish.PNG)

editamos y cambiamos 





![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)



**Ejercicio 2:**
llamar a una API web mediante c�digo del lado del servidor

En este ejercicio, llamar� a la API web que desarroll� en el ejercicio anterior utilizando la clase HttpClient. Para hacer esto, primero registrar� el servicio IHttpClientFactory en el archivo Startup.cs. Luego, crear� un controlador MVC y usar� la clase HttpClient para llamar a una acci�n Get en la API web. Despu�s de eso, crear� otro controlador MVC y usar� la clase HttpClient para llamar a una acci�n de publicaci�n en la API web. Finalmente, agregar� una acci�n al controlador MVC en la que usar� la clase HttpClient para llamar a una acci�n Get en la API web que obtiene un par�metro.

Las principales tareas de este ejercicio son las siguientes:

1.Llamar a un m�todo Get de API web

2.Ejecutar la aplicaci�n

3.Llamar a un m�todo de publicaci�n de API web

4.Llamar a un m�todo Get de API web que obtiene un par�metro

5.Ejecutar la aplicaci�n


![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)




**Ejercicio 3:**
llamar a una API web mediante jQuery

En este ejercicio, llamar� a una API web mediante jQuery. Primero crear� un controlador MVC y usar� jQuery para llamar a una acci�n Get en la API web. Despu�s de eso, crear� otro controlador MVC y usar� jQuery para llamar a una acci�n Publicar en la API web.

Las principales tareas de este ejercicio son las siguientes:

1.Llamar a un m�todo Get de API web mediante jQuery

2.Ejecutar la aplicaci�n

3.Llamar a un m�todo Get de API web mediante HttpClient

4.Llamar a un m�todo de publicaci�n de API web mediante jQuery

5.Ejecutar la aplicaci�n

![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)
![subir_estos](C:\Users\Juanjo\Desktop\subir_estos.PNG)


Hemos cambiado c�digo para que coja las imagenes de local y si no hay pues del BlobStorage