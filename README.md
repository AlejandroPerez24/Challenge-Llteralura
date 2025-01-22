📘 Proyecto Java Spring - Literalura
Desarrollado por Alejandro Quiñonez Perez para Alura Latam

Este proyecto utiliza Java 17 y Spring Boot como base para construir aplicaciones backend robustas y eficientes. Sirve como un punto de partida versátil para proyectos que priorizan la lógica de negocio y el manejo de datos.

📖 Descripción
Literalura es una aplicación de consola que permite la gestión básica de una base de datos de libros. Diseñado pensando en la simplicidad y la funcionalidad, este proyecto implementa características clave para demostrar el poder de Spring Boot en el desarrollo backend.

✨ Características principales
Búsqueda precisa de libros por título
Los usuarios pueden buscar libros ingresando palabras clave del título directamente desde la consola. Por ejemplo, al buscar "Pride", el sistema devolverá resultados como Pride and Prejudice si están disponibles en la base de datos.

Configuración sencilla y adaptable
La aplicación utiliza una configuración modular para conectarse a bases de datos y gestionar registros fácilmente.

⚙️ Consideraciones técnicas
Diseñada exclusivamente para entorno de consola, eliminando la necesidad de frontend.
Integración con Spring Data JPA para manejo eficiente de bases de datos.
Estructura preparada para escalabilidad y nuevas funcionalidades.
🎯 Objetivo
Proveer una plantilla inicial para proyectos basados en Java y Spring Boot, enfocándose en:

Implementar prácticas modernas de desarrollo backend.
Facilitar la gestión y búsqueda de datos.
Servir como ejemplo de buenas prácticas en aplicaciones orientadas a datos.
🛠️ Requisitos
Antes de iniciar, asegúrate de contar con las siguientes herramientas instaladas en tu sistema:

-Java 17
-Maven 3.6+
-Git

Configurar el archivo application.properties
Ajusta las credenciales y parámetros de conexión a la base de datos según tu entorno.

	
# Configuración de la aplicación  
spring.application.name=literalura  

# Conexión a la base de datos  
spring.datasource.url=jdbc:mysql://localhost/literalura  
spring.datasource.username=root  
spring.datasource.password=admin  
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver  

# Configuración de Hibernate  
spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect  
spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  
spring.jpa.format-sql=true  