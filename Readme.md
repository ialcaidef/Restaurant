## Implementando Web APIs

Se crea una aplicación web para un restaurante. Para ello, se crea una página que muestra todas las sucursales del restaurante, 
permite que los usuarios soliciten una reserva para el restaurante seleccionado, añade una página de anuncios de búsqueda y 
permite el envío de una solicitud para un puesto de trabajo seleccionado.

Se crea una aplicación Web API del lado del servidor y una aplicación ASP.NET Core MVC del lado del cliente. En la aplicación del lado del 
cliente, se llamará a las acciones de la API Web utilizando HttpClient y jQuery.

Objetivos

- Agregar acciones a una aplicación Web API.
- Llamar a las acciones de la API Web mediante el uso de HttpClient.
- Llamar a las acciones de la API web utilizando jQuery.


**1: Añadir acciones y llamarlas usando un navegador

Primero se agregará un controlador y una acción a una aplicación Web API. A continuación, se ejecutará la aplicación y se verá el resultado 
utilizando un navegador. Después de esto, se agregará un controlador y una acción que obtiene un parámetro. A continuación, 
se ejecutará la aplicación y verá el resultado utilizando un navegador. Por último, se agregará una acción Post a la aplicación de la API Web.

Las principales tareas son:

	1. Añadir un controlador y una acción a una aplicación de la API web
	2. Ejecute la aplicación
	3. Añade un controlador y una acción que obtiene un parámetro
	4. Ejecute la aplicación
	5. Añadir una acción de publicación a una aplicación Web API


**2: Llamar a una Web API usando el código del lado del servidor

Llamaremos al API Web que desarrollamos en el punto anterior utilizando la clase HttpClient. 
Para ello, primero se registra el servicio IHttpClientFactory en el archivo Startup.cs. A continuación, se crea un controlador MVC y 
se utilizara la clase HttpClient para llamar a una acción Get en la Web API. A continuación, se crea otro controlador MVC y se utiliza la clase 
HttpClient para llamar a una acción Post en la API Web. Por último, se añade una acción al controlador MVC en la que se utiliza la clase HttpClient 
para llamar a una acción Get en la API Web que obtenga un parámetro.

Las principales tareas son:

	1. Llamar a un método Get de la API Web
	2. Ejecute la aplicación
	3. Llamar a un método de publicación de la API Web
	4. Llamando al método GET del API Web obtener un parámetro
	5. Ejecute la aplicación


**3: Llamar a una API Web usando jQuery


Primero creamos un controlador MVC y utilizamos jQuery para llamar a una acción Get en la API web. Después, se crea otro controlador MVC y
se utiliza jQuery para llamar a una acción Post en la API web. 

Las principales tareas son:

1. Llamar a un método Get de la API Web usando jQuery
2. Ejecute la aplicación
3. Llamar a un método Get de la API Web usando HttpClient
4. Llamar a un método Post de la API Web usando jQuery
5. Ejecute la aplicación
