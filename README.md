# Análisis de la atención al público en cadena de electrodomésticos en Argentina
Análisis estadístico automatizado de comentarios de Google Maps 

Utilizaremos Python, NLP, Web Scrapping y Análisis de Sentimiento para abordar un estudio estadístico de los comentarios que dejan los clientes
en la sección opiniones de las tiendas que aparecen en Google Maps.

Selecciono para este estudio una de las cadenas con mayor antigüedad en el rubro. Tomo algunos locales al azar de las ciudades de Buenos Aires, Córdoba, Rosario y Mar del Plata.

# Introducción

Recopilar reseñas manualmente desde Google Maps es un enfoque exhaustivo que solo es factible para nichos de mercado pequeños con una cantidad limitada de reseñas. Alternativamente se pueden utilizar API pagas que simplifican el proceso mediante el raspado web o también podemos crear nuestro propio script de raspado sin costo. En este trabajo exploraremos la última opción.
Antes que nada explicaremos brevemente a qué denominamos "raspado" o "Web Scrapping". Web scraping o raspado web es una técnica utilizada mediante programas de software para extraer información de sitios web. Usualmente, estos programas simulan la navegación de un humano en la World Wide Web, ya sea utilizando el protocolo HTTP manualmente o incrustando un navegador en una aplicación.

Corremos inicialmente un programa en Python que realiza la tarea de recopilar las opiniones de los clientes de cada sucursal de la cadena y guarda los resultados en un archivo Excel para su posterior análisis.



