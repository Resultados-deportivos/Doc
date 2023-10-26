# A realizar
* Contenga el acceso al resto de apartados de la web. Adicionalmente destacará los eventos que se estén produciendo en el momento y podría contener, además, noticias destacadas.
* Página o páginas con resultados deportivos ya terminados.
* Página o páginas con el calendario de eventos futuros.
* Seguimiento de eventos deportivos en vivo.
* Posibilidad de registrarse para (ejemplos):
  * dar likes (y/o dislikes)
    * añadir comentarios
    * participar en encuestas
    * cualquier otra funcionalidad
* Página o páginas de gestión, para:
  *  Crear eventos en vivo
  * Introducir resultados deportivos
  * Editar (corregir) resultados etc
## La web tiene que estar publicada en internet bajo una URL. De esta web se realizará un seguimiento de las visitas:
* Cantidad de visitas en total por período
* Seguimiento de páginas internas más visitadas
* Términos de búsqueda (keywords) que se han conseguido posicionar en Google u otros buscadores.
 La accesibilidad y usabilidad de la interfaz deben ser considerados, con el objetivo de maximizar las visitas para incrementar la capacidad de indexación de los buscadores como siendo inclusivo para gente con alguna discapacidad.
## En la parte servidor:
* La aplicación se desarrollará en Python, siguiendo el patrón Modelo-Vista-Controlador (MVC).
* No se utilizará ningún framework para el desarrollo.
* Se utilizará el motor de plantillas Jinja2 para incrustar los datos dinámicos en la/s página/s HTML.
* Se guardarán los resultados en una base de datos PostgreSQL
* Se trabajará con el ORM (Object Relational Mapping )  SQLAlchemy.
* Se dispondrá de un proceso que recibe peticiones y las devuelve en formato JSON.
* Se valorará positivamente el consumo de alguna API para recoger información desde Python, así como la utilización de un botón de refresco o similar, para actualizar la información.

## En la parte cliente:
* Encargada de presentar la información
* Solicita datos a servidor y procesa el JSON recibido.
* El diseño debe ser responsive, es decir debe adaptarse a diferentes contexto; mínimo debe de adaptarse de forma correcta a resoluciones de móviles, tabletas y ordenadores.
* Se valorará el uso adecuado de CSS Grid, Flexbox y sus combinaciones posibles. A su vez, el uso correcto de pseudo-elementos y pseudo-clases.
* La utilización de algún pre-procesador de CSS también será valorado positivamente.
## Prestar especial atención a:
* Referenciar todas las fuentes utilizadas. Se debe especificar la estrategia de búsqueda utilizada y la fiabilidad de las fuentes. 
*Recoger correctamente las citas utilizadas.   https://classroom.google.com/u/0/w/MzY2MTQ4NTM2OTMz/t/all?hl=es
* Utilizar un lenguaje escrito y gráfico inclusivo en toda la documentación, que forme parte de los entregables del reto. Asimismo dicho lenguaje inclusivo estará presente en toda la comunicación tanto escrita como oral. https://classroom.google.com/u/0/w/MzY2MTQ4NTM2OTMz/t/all?hl=es
