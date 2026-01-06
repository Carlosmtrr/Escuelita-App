# 🏫 Sistema de Gestión Escolar (Escuelita-App)

> Un sistema ERP educativo robusto diseñado para la gestión eficiente de alumnos, docentes y calificaciones.

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📋 Descripción del Proyecto

**Escuelita-App** es una plataforma web desarrollada bajo el patrón de arquitectura **MVC**, enfocada en la escalabilidad y la seguridad de datos. Este sistema soluciona la necesidad de administrar grandes volúmenes de información académica mediante una interfaz intuitiva y procesos optimizados en el backend.

El proyecto demuestra la implementación de prácticas profesionales de desarrollo como **autenticación segura, control de acceso basado en roles (RBAC) y optimización de consultas SQL**.

## 🚀 Características Principales

* **Arquitectura MVC:** Separación clara de la lógica de negocio, datos e interfaz de usuario para facilitar el mantenimiento.
* **Seguridad Avanzada (RBAC):** Sistema de permisos granular.
    * *Administrador:* Acceso total al sistema.
    * *Docente:* Gestión de calificaciones y asistencias.
    * *Alumno:* Consulta de historial académico.
* **Gestión de Datos (CRUDs):** Operaciones complejas optimizadas para alumnos, materias y grupos.
* **Reportes:** Generación de vistas para el seguimiento académico.
* **Autenticación:** Login seguro y protección de rutas mediante Middleware.

## 🛠️ Tecnologías Utilizadas

* **Backend:** PHP 8.x, Laravel Framework.
* **Base de Datos:** MySQL (Diseño relacional optimizado).
* **Frontend:** HTML5, CSS3, JavaScript, Blade Templates.
* **Herramientas:** Git, Composer, Artisan.

## ⚙️ Instalación y Configuración

Si deseas correr este proyecto en local, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/Carlosmtrr/Escuelita-App.git](https://github.com/Carlosmtrr/Escuelita-App.git)
    ```
2.  **Instalar dependencias de PHP:**
    ```bash
    composer install
    ```
3.  **Configurar entorno:**
    * Duplica el archivo `.env.example` y renómbralo a `.env`.
    * Configura tus credenciales de base de datos en el archivo `.env`.
4.  **Generar llave de aplicación:**
    ```bash
    php artisan key:generate
    ```
5.  **Migrar la base de datos:**
    ```bash
    php artisan migrate
    ```
6.  **Correr el servidor:**
    ```bash
    php artisan serve
    ```

## 👤 Autores

**Carlos Morán Torres**
* 📧 Email: [carlosmoran0119@gmail.com](mailto:carlosmoran0119@gmail.com)
* 🐙 GitHub: [@Carlosmtrr](https://github.com/Carlosmtrr)
  
**Erick de la Barrera López**
* 📧 Email: [erickdelab@gmail.com](mailto:erickdelab@gmail.com)
* 🐙 GitHub: [@erickdelab](https://github.com/erickdelab)

---
*Desarrollado como parte del portafolio profesional de Ingeniería en TIC.*
