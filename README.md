# Análisis exploratorio: librería online
__Análisis de datos mediante consultas SQL__

<image src="https://github.com/BastianLQ/Analisis-SQL-Libreria/blob/main/Images/banner.png" alt="banner">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P14SQL.html)_

## Descripción del Proyecto
El coronavirus tomó al mundo entero por sorpresa, cambiando la rutina diaria de todos y todas. Los habitantes de las ciudades ya no pasaban su tiempo libre fuera, yendo a cafés y centros comerciales; sino que más gente se quedaba en casa, leyendo libros. Eso atrajo la atención de las startups (empresas emergentes) que se apresuraron a desarrollar nuevas aplicaciones para los amantes de los libros.

Se ha proporcionado una base de datos de uno de los servicios que compiten en este mercado. Contiene datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros. Esta información se utilizará para generar una propuesta de valor para un nuevo producto.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, SQLAlchemy.

## Proceso del Proyecto
El proyecto se dividió en dos fases:
- __Preparativos:__ Importar las librerías necesarias, optimizar el proceso de realizar las consultas en SQL y previsualizar las tablas.
- __Análisis:__ Responder 5 preguntas clave sobre el e-commerce de libros.

## Base de datos

<image src="https://github.com/BastianLQ/Analisis-SQL-Libreria/blob/main/Images/Image.png" alt="banner">

Se puede apreciar una base de datos de cuatro tablas, con información sobre los libros, autores, ratings, reviews y editoriales.

## Descubrimientos importantes
A partir de las consultas realizadas a la base de datos proporcionada, se han recopilado las siguientes conclusiones.

- El número de libros publicados desde el 1 de enero de 2000 es de 819.
- Con 42 publicaciones, Penguin Books es la editorial que más libros (textos de más de 50 páginas) ha lanzado.
- Diana Gabaldon es la autora mejor calificada con un promedio de 4.3 estrellas de un total de 5.
- El número promedio de reseñas (reviews) de texto entre los usuarios que calificaron (rating) más de 50 libros es de 24.3

A partir del último punto (y como se menciona en el bloque anterior) se puede presuponer que los usuarios que escriben reseñas generalmente calfican (y por lo tanto leen) varios libros, incentivar a los usuarios a calificar sus lecturas podría ser un buen primer paso para aumentar la cantidad de reseñas escritas, esto debido a que una calificación es menos invasiva y requiere menos esfuerzo que escribir una reseña, y a su vez, una reseña escrita puede resultar más útil para un potencial comprador que una calificación.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P14SQL.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba.
