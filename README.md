API Creator

Este es un proyecto de demostración creado con Spring Boot que expone una API REST básica. La API tiene los siguientes endpoints para procesar solicitudes HTTP con métodos GET, POST, PUT y DELETE.
Descripción

Este proyecto utiliza Spring Boot para crear una API simple con los siguientes endpoints:

    GET /hello: Devuelve un mensaje de saludo con el nombre que se pase como parámetro.

    POST /hello: Procesa el nombre enviado en el cuerpo de la solicitud y devuelve un mensaje de saludo.

    PUT /hello: Actualiza un recurso con el nombre enviado en el cuerpo de la solicitud y devuelve un mensaje de saludo.

    DELETE /hello: Procesa la solicitud de eliminación para el nombre enviado en el cuerpo de la solicitud.

Tecnologías utilizadas

    Spring Boot 3.5.0

    Java 17

Instalación
Requisitos previos

Asegúrate de tener Java 17 y Maven instalados en tu máquina.
Clonar el repositorio

Para clonar este proyecto, usa el siguiente comando:

git clone https://github.com/DIdiernmg/api_creator.git

Instalar dependencias

Accede al directorio del proyecto y ejecuta el siguiente comando para instalar las dependencias:

mvn install

Ejecución

Para ejecutar la aplicación, puedes usar el siguiente comando:

mvn spring-boot:run

Esto iniciará la aplicación en http://localhost:8080.
Uso de la API
Endpoint GET

    URL: /hello

    Método: GET

    Descripción: Devuelve un saludo con el nombre que se pase como parámetro.

Ejemplo: GET http://localhost:8080/hello?name=John

    Respuesta:

"Hello, John"

Endpoint POST

    URL: /hello

    Método: POST

    Descripción: Devuelve un saludo con el nombre enviado en el cuerpo de la solicitud.

Ejemplo: POST http://localhost:8080/hello

    Cuerpo de la solicitud:

"Jane"

    Respuesta:

"Hello, Jane - Processed with POST!"

Endpoint PUT

    URL: /hello

    Método: PUT

    Descripción: Actualiza un recurso con el nombre enviado en el cuerpo de la solicitud.

Ejemplo: PUT http://localhost:8080/hello

    Cuerpo de la solicitud:

"John"

    Respuesta:

"Hello, John - Updated with PUT!"

Endpoint DELETE

    URL: /hello

    Método: DELETE

    Descripción: Procesa la solicitud de eliminación para el nombre enviado en el cuerpo de la solicitud.

Ejemplo: DELETE http://localhost:8080/hello

    Cuerpo de la solicitud:

"Jane"

    Respuesta:

"Hello, Jane - Processed with DELETE!"

Contribuciones

Si deseas contribuir a este proyecto, por favor, haz un fork del repositorio, realiza tus cambios y envía un pull request.
