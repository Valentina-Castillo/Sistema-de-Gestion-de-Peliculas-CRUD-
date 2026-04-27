# Sistema-de-Gesti-n-de-Pel-culas-CRUD-
Aplicación web desarrollada en Java EE con JSP, Servlets y MySQL, creada desde cero en Eclipse. El sistema implementa un CRUD completo para la gestión de un catálogo de películas.

🚀 Tecnologías utilizadas
☕ Java (POO)
🌐 JSP (Java Server Pages)
⚙️ Servlets (Controladores MVC)
🗄️ MySQL Server
🔗 JDBC
🎨 HTML5 + CSS3
🧠 Eclipse IDE
📦 Apache Tomcat
🧠 Arquitectura del proyecto

El proyecto sigue patrón MVC (Modelo - Vista - Controlador):

-Modelo:
  Clases peliculas, genero, directores
  Acceso a datos mediante consultas SQL
-Vista:
  JSP dinámicos
  Formularios HTML integrados
  Interfaz personalizada
-Controlador:
  Servlets que gestionan todas las peticiones HTTP
  Lógica de negocio y flujo de datos
  Constantes:
  Clase I_Constantes para centralizar parámetros y atributos

🎯 Funcionalidades principales (CRUD completo)

✔ Crear películas (INSERT)
✔ Listar películas (SELECT)
✔ Modificar películas (UPDATE)
✔ Eliminar películas (DELETE)
✔ Guardar cambios en base de datos MySQL en tiempo real

🔍 Funcionalidades adicionales

✔ Búsqueda de películas por título
✔ Filtro por género
✔ Filtro por director
✔ Gestión de relaciones entre tablas
✔ Visualización de imágenes por película
✔ Interfaz personalizada estilo cine

🗄️ Base de datos

Base de datos creada en MySQL Server desde cero, con tablas principales:

-peliculas
-genero
-directores

Relaciones:

-Cada película está asociada a un género
-Cada película está asociada a un director

Conexión realizada mediante JDBC desde Eclipse.

🎬 Descripción del proyecto

Este proyecto simula un sistema real de gestión de catálogo cinematográfico donde se puede:

-Insertar nuevas películas en la base de datos
-Editar información existente
-Eliminar registros
-Consultar y filtrar datos dinámicamente

Todo el sistema está conectado en tiempo real con MySQL, garantizando persistencia de datos.

💡 Objetivo

El objetivo del proyecto es practicar:

Desarrollo web con Java EE
Arquitectura MVC
Conexión entre backend y base de datos
Gestión completa de CRUD
Manejo de JSP y Servlets
Estructuración de proyectos reales en Eclipse

🚀 Mejoras futuras
Login de usuarios (autenticación)
Roles (admin / usuario)
Subida real de imágenes
API REST con JSON
Migración a Spring Boot
UI moderna con framework frontend

👩‍💻 Autor
Valentina Castillo (https://www.linkedin.com/in/valentina-castillo-escobar-191863202/)
Proyecto desarrollado como práctica de desarrollo web full stack con Java.
