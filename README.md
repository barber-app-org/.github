# 🏠 Barber Shop - Microservices Architecture  

Este proyecto implementa un sistema para la gestión de una barbería utilizando una arquitectura basada en microservicios con **Spring Boot** y otras tecnologías modernas.  

## 📁 **Estructura del Proyecto**  

El sistema está compuesto por **4 microservicios principales**:  

1. **Users Service** 🧑‍💼  
   - Gestiona la información de los usuarios (clientes y barberos).  
   - Funcionalidades: Registro, autenticación y gestión de usuarios.  
   
2. **Appointments Service** 📅  
   - Permite la gestión de citas entre clientes y barberos.  
   - Funcionalidades: Reservar, cancelar y modificar citas.  

3. **Payments Service** 💳  
   - Maneja los pagos y facturación de los servicios de la barbería.  
   - Integración con métodos de pago.  

4. **Notifications Service** 📩  
   - Envia notificaciones por email/SMS a los clientes y barberos.  
   - Notifica confirmaciones y recordatorios de citas.  

## 🛠️ **Tecnologías Utilizadas**  

- **Java 17** + **Spring Boot 3**  
- **Spring Cloud** (para comunicación entre microservicios)  
- **Spring Security & JWT** (para autenticación y autorización)  
- **Spring Data JPA** + **MySQL** (para la persistencia de datos)  
- **RabbitMQ** (para comunicación asíncrona entre servicios)  
- **Eureka Server** (para el registro y descubrimiento de servicios)  
- **API Gateway** (para enrutar solicitudes a los microservicios)  
- **Docker & Docker Compose** (para la contenedorización)  
- **Swagger / OpenAPI** (para la documentación de APIs)  

## ⚙️ **Configuración y Ejecución**  

### 🔹 1. Clonar el repositorio  
```bash
git clone https://github.com/tu-usuario/barber-shop.git
cd barber-shop
