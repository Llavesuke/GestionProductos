# Productos MVC

Esta es una aplicación Spring Boot para gestionar productos.

## Requisitos

- Java 17 o superior
- Maven 3.6.0 o superior

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/Llavesuke/GestionProductos
    cd GestionProductos
    ```
## Ejecución

1. Ejecuta la aplicación usando Maven:

    ```bash
    mvn spring-boot:run
    ```

2. La aplicación estará disponible en `http://localhost:8080`.

## Uso

- Para ver la lista de productos, navega a `http://localhost:8080/products`.
- Para agregar un nuevo producto, navega a `http://localhost:8080/products/new`.

## Estructura del Proyecto

- `src/main/java/com/example/productosmvc` - Código fuente de la aplicación.
- `src/main/resources/templates` - Plantillas Thymeleaf.
- `src/main/resources/static` - Archivos estáticos (CSS, JS, imágenes).
