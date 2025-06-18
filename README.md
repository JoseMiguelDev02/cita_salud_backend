# 🩺 CitaSaludFeature3 — Backend

Backend del módulo de gestión de horarios y médicos para el sistema **CitaSaludFeature3**, desarrollado con **Spring Boot**. Este backend soporta las funcionalidades definidas en las historias de usuario **HU001** y **HU002**.

## 🚀 Tecnologías utilizadas

- **Java 19** – Lenguaje principal del proyecto
- **Spring Boot** – Framework para desarrollo rápido de microservicios
- **Spring Web** – Para creación de APIs REST
- **Spring Data JPA** – Acceso a base de datos
- **PostgreSQL** – Motor de base de datos
- **MapStruct** – Mapeo entre entidades y DTOs
- **Swagger / OpenAPI** – Documentación de endpoints
- **Maven** – Gestión de dependencias y compilación

## 📁 Estructura del proyecto

├── controller/ # Controladores REST

├── domain/ # Entidades del modelo de dominio

├── dto/ # Data Transfer Objects

├── mapper/ # Clases de mapeo entre entidades y DTOs

├── repository/ # Interfaces JPA para acceso a datos

├── service/ # Interfaces y clases de lógica de negocio

├── config/ # Configuración de seguridad y otras

└── application/ # Clase principal para ejecución del backend


## 🎯 Endpoints principales

![Capturaendpoints1](https://github.com/user-attachments/assets/3764a71b-96d5-41b7-a6b0-359daebcab4f)
![Capturaendpoints2](https://github.com/user-attachments/assets/fae3c139-b654-44f9-a180-946635c33d5a)

### HU001 - Franjas horarias
- `GET /api/franjas/listarfranjas`
- `POST /api/franjas/{id}`
- `PUT /api/franjas/{idFranja}`
- `DELETE /api/franjas/{idFranja}`

### HU002 - Médicos
- `GET /api/medicos/obtenermedicos`
- `POST /api/medicos/crearmedico`
- `GET /api/medicos/confranjas`

### HU005 - Login de perfiles
- `POST /api/auth/login`

### HU006 - Perfil con derecho de modificación
- `GET /api/usuarios/perfil`
- `PUT /api/usuarios/actualizar`

[📁 Ver informe en Google Drive](https://drive.google.com/drive/folders/1XUitjg92WoS88TUI2N9mPXSZcm5BNcuW?usp=sharing)

## 🌐 Despliegue

Accede a la versión actual del backend con Swagger UI en:

🔗 [https://citasaludfeature3.onrender.com/swagger-ui/index.html#/](https://citasaludfeature3.onrender.com/swagger-ui/index.html#/)

Accede a la versión desplegada del frontend en:

🔗 [https://cita-salud-feature3-frontend.vercel.app](https://cita-salud-feature3-frontend.vercel.app/)




