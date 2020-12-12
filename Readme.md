## Implementando Web APIs

Se crea una aplicaci�n web para un restaurante. Para ello, se crea una p�gina que muestra todas las sucursales del restaurante, 
permite que los usuarios soliciten una reserva para el restaurante seleccionado, a�ade una p�gina de anuncios de b�squeda y 
permite el env�o de una solicitud para un puesto de trabajo seleccionado.

Se crea una aplicaci�n Web API del lado del servidor y una aplicaci�n ASP.NET Core MVC del lado del cliente. En la aplicaci�n del lado del 
cliente, se llamar� a las acciones de la API Web utilizando HttpClient y jQuery.

Objetivos

- Agregar acciones a una aplicaci�n Web API.
- Llamar a las acciones de la API Web mediante el uso de HttpClient.
- Llamar a las acciones de la API web utilizando jQuery.


**1: A�adir acciones y llamarlas usando un navegador**

Primero se agregar� un controlador y una acci�n a una aplicaci�n Web API. A continuaci�n, se ejecutar� la aplicaci�n y se ver� el resultado 
utilizando un navegador. Despu�s de esto, se agregar� un controlador y una acci�n que obtiene un par�metro. A continuaci�n, 
se ejecutar� la aplicaci�n y ver� el resultado utilizando un navegador. Por �ltimo, se agregar� una acci�n Post a la aplicaci�n de la API Web.

Las principales tareas son:

	1. A�adir un controlador y una acci�n a una aplicaci�n de la API web
	2. Ejecute la aplicaci�n
	3. A�ade un controlador y una acci�n que obtiene un par�metro
	4. Ejecute la aplicaci�n
	5. A�adir una acci�n de publicaci�n a una aplicaci�n Web API


2: Llamar a una Web API usando el c�digo del lado del servidor

Llamaremos al API Web que desarrollamos en el punto anterior utilizando la clase HttpClient. 
Para ello, primero se registra el servicio IHttpClientFactory en el archivo Startup.cs. A continuaci�n, se crea un controlador MVC y 
se utilizara la clase HttpClient para llamar a una acci�n Get en la Web API. A continuaci�n, se crea otro controlador MVC y se utiliza la clase 
HttpClient para llamar a una acci�n Post en la API Web. Por �ltimo, se a�ade una acci�n al controlador MVC en la que se utiliza la clase HttpClient 
para llamar a una acci�n Get en la API Web que obtenga un par�metro.

Las principales tareas son:

	1. Llamar a un m�todo Get de la API Web
	2. Ejecute la aplicaci�n
	3. Llamar a un m�todo de publicaci�n de la API Web
	4. Llamando al m�todo GET del API Web obtener un par�metro
	5. Ejecute la aplicaci�n


3: Llamar a una API Web usando jQuery


Primero creamos un controlador MVC y utilizamos jQuery para llamar a una acci�n Get en la API web. Despu�s, se crea otro controlador MVC y
se utiliza jQuery para llamar a una acci�n Post en la API web. 

Las principales tareas son:

1. Llamar a un m�todo Get de la API Web usando jQuery
2. Ejecute la aplicaci�n
3. Llamar a un m�todo Get de la API Web usando HttpClient
4. Llamar a un m�todo Post de la API Web usando jQuery
5. Ejecute la aplicaci�n