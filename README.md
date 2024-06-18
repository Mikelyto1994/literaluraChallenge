# Challenge Literalura 👩‍💻
## ¡Bienvenido(a) a Literalura! 📚
Literalura es una aplicación que te permite gestionar tu biblioteca personal de libros.

## ¿Qué puedes hacer con Literalura? 📋
- Buscar libros por título o autor.
- Listar libros y autores registrados.
- Buscar autores vivos en un año específico.
- Listar libros por idioma.
- Obtener el top 10 de libros más buscados.
- Generar estadísticas sobre las descargas de libros.

## ¿Cómo funciona Literalura? 👩‍🏫
Literalura utiliza una API externa para obtener información sobre libros y autores: https://gutendex.com/ 
También almacena información en una base de datos local para que puedas acceder a ella incluso sin conexión a internet.

## ¿Cómo empezar? 🖥️

### Clona el repositorio:
`git clone https://github.com/Mikelyto1994/literaluraChallenge`

### Instala las dependencias:
Se usa el entoro de desarrollo Integrado (IDE) - IntellijIdea para este caso de estudio.

### Ejecuta la aplicación:
Previo a ello, se anexa los datos a la base de datos relacional que tienes que crear en Postgress SQL 15 (PGADMIN)
Crear la tabla de datos "dbalura", para ello se recomienda ver modulos anteriores de la clase Alura sobre como se hace ello

## Estructura del proyecto:
- src/main/java:
  - com.alura.literalura:
    - model: Contiene las clases que representan los datos de libros y autores.
    - repository: Contiene las interfaces y clases que se utilizan para acceder a la base de datos.
    - service: Contiene las clases que implementan la lógica de negocio de la aplicación.
    - principal: Contiene la clase principal de la aplicación.
- src/main/resources: Contiene los archivos de configuración de la aplicación.
- pom.xml: Contiene las dependencias del proyecto.

## Mejoras que puedas observar:
Si tienes alguna mejora que puedas presenciar de este challenge, te agradecería que me indiques,
El API para este desarollo no contiene más de 

## Tecnologías utilizadas:
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
