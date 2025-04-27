<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Acerca de App Delivery PHP

# App Delivery PHP

App Delivery PHP es una aplicación web desarrollada en **Laravel 12** que permite a los usuarios realizar pedidos de
comida en línea de forma rápida y sencilla.

El sistema cuenta con un panel de administración para la gestión de productos, barrios de entrega, pedidos, clientes y
repartidores, ofreciendo una solución completa para servicios de delivery locales.

## Requisitos

Antes de comenzar, asegúrate de tener instalado:

- **PHP** >= 8.2
- **Composer** (para la gestión de dependencias de PHP)
- **Laravel 12**
- **Node.js** >= 23 (para la gestión de assets con Vite)
- **NPM** o **Yarn**
- **MySQL** o **MariaDB** (para la base de datos)

## Instalación

Sigue los pasos a continuación para instalar y ejecutar el proyecto en tu entorno local:

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/tu-usuario/foodiedelivery.git
   cd foodiedelivery
   ```

2. **Instalar las dependencias de PHP:**

   ```bash
   composer install
   ```

3. **Instalar las dependencias de JavaScript:**

   ```bash
   npm install
   ```

4. **Configurar el archivo de entorno `.env`:**

   Copia el archivo `.env.example` y renómbralo a `.env`:

   ```bash
   cp .env.example .env
   ```

5. **Generar la clave de la aplicación:**

   ```bash
   php artisan key:generate
   ```

6. **Configurar la base de datos:**

   Edita el archivo `.env` y actualiza las variables relacionadas con la conexión a la base de datos:

   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=nombre_de_tu_base_de_datos
   DB_USERNAME=tu_usuario
   DB_PASSWORD=tu_contraseña
   ```

7. **Ejecutar migraciones:**

   ```bash
   php artisan migrate
   ```

8. **Compilar los assets:**

   Para desarrollo:

   ```bash
   npm run dev
   ```

   Para producción:

   ```bash
   npm run build
   ```

9. **Levantar el servidor de desarrollo:**

   ```bash
   php artisan serve
   ```

Ahora puedes acceder a la aplicación en `http://localhost:8000`.


