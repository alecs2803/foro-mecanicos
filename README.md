  <h1>Foro de Mecánicos - Backend</h1>
    <p>Una poderosa API RESTful creada con <strong>Spring Boot</strong>, que sirve como base para un foro donde los mecánicos pueden compartir conocimientos, resolver dudas técnicas y colaborar en soluciones prácticas. Este proyecto fue desarrollado por <strong>Oscar Alejandro Gonzalez Contreras</strong>, apasionado por la tecnología y el desarrollo de soluciones eficientes.</p>

   <h2>Características</h2>
    <ul>
        <li><strong>Registro de preguntas:</strong> Los usuarios pueden crear preguntas para ser respondidas.</li>
        <li><strong>Respuesta a preguntas:</strong> Otros usuarios pueden responder las preguntas registradas.</li>
        <li><strong>Listado de preguntas:</strong> Se pueden listar todas las preguntas, tanto contestadas como no contestadas.</li>
        <li><strong>Filtrado de preguntas contestadas:</strong> Ver únicamente las preguntas que ya han sido respondidas.</li>
  <li><strong>Consulta específica:</strong> Consultar una pregunta específica por su ID.</li>
        <li><strong>Edición de preguntas contestadas:</strong> Modificar el contenido de preguntas que ya han sido respondidas.</li>
        <li><strong>Autenticación:</strong> Requiere inicio de sesión para acceder a todas las funcionalidades.</li>
    </ul>

   <h2>Tecnologías utilizadas</h2>
    <ul>
        <li><strong>Java 17</strong></li>
        <li><strong>Spring Boot:</strong> Framework principal para la construcción de la aplicación.</li>
        <li><strong>Spring Web:</strong> Manejo de endpoints y arquitectura REST.</li>
        <li><strong>Spring Security:</strong> Implementación de autenticación y autorización mediante tokens JWT.</li>
        <li><strong>Hibernate/JPA:</strong> Manejo de la persistencia de datos y mapeo objeto-relacional.</li>
        <li><strong>Base de datos SQL:</strong> Configurable según las necesidades del usuario.</li>
        <li><strong>Insomnia:</strong> Herramienta utilizada para probar y consumir los endpoints de la API.</li>
    </ul>
    <h2>Endpoints principales</h2>
    <h3>Autenticación</h3>
    <ul>
        <li><code>POST /login</code> - Iniciar sesión y obtener un token.</li>
    </ul>
    <h3>Preguntas</h3>
    <ul>
        <li><code>POST /preguntas</code> - Registrar una nueva pregunta.</li>
        <li><code>GET /preguntas</code> - Listar todas las preguntas.</li>
        <li><code>GET /preguntas/contestadas</code> - Listar solo las preguntas que han sido respondidas.</li>
        <li><code>GET /preguntas/{id}</code> - Consultar una pregunta específica por ID.</li>
        <li><code>PUT /preguntas/{id}</code> - Editar una pregunta ya contestada.</li>
    </ul>
    <h3>Respuestas</h3>
    <ul>
        <li><code>POST /preguntas/{id}/respuesta</code> - Responder una pregunta específica.</li>
    </ul>

  <h2>Requisitos previos</h2>
    <ul>
        <li>Java 17 o superior</li>
        <li>Insomnia (o cualquier cliente de API REST)</li>
        <li>Base de datos configurada (detalles en el archivo de configuración)</li>
    </ul>

  <h2>Instalación y ejecución</h2>
    <ol>
        <li>Clona este repositorio:
            <pre><code>git clone https://github.com/alecs2803/foro-mecanicos.git</code></pre>
        </li>
        <li>Configura el archivo <code>application.properties</code> con los datos de tu base de datos.</li>
        <li>Ejecuta el proyecto:
            <pre><code>./mvnw spring-boot:run</code></pre>
        </li>
    </ol>
    <h2>Uso</h2>
    <ol>
        <li>Usa Insomnia para enviar solicitudes HTTP a los endpoints listados.</li>
        <li>Autentícate con las credenciales configuradas para obtener un token.</li>
        <li>Explora las funcionalidades como registrar, responder y listar preguntas.</li>
    </ol>
    <h2>Contribuciones</h2>
    <p>¡Contribuciones son bienvenidas! Si deseas colaborar, por favor contactame a camaradaloradha@hotmail.com.</p>
    
    
</body>
</html>





