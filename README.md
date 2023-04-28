# 3rdpartysolution_demo

**3rdpartysolution_demo** is **Laravel 8** demo which is integrated with [**Metronic Themes**](https://keenthemes.com/metronic/) by [**Keenthemes**](https://keenthemes.com/) built on **Bootstrap 5**

### Features
  - Metronic Dashboard
  - Layout Configuration
  - Menu
  - Multi-step Modal
  - Full Calendar
  - Various Progress bar
  - Fancy Chart

Note:
> Currently using blade templating dashboard layout

### Selected Theme
  Metronic Dashboard: [Demo](https://preview.keenthemes.com/seven-html-free/?page=index)

### Package
  - Laravel 8.75
  - Metronic 7.x
  - Bootstrap 4

### Requirement

* PHP 7.3.x +
* Composer 2.0.x +
* Node.js 12.16.x +

### Installation

1. Run the following command 
    ```sh
    git clone https://github.com/dragonrathony/3rdpartysolution_demo
    ```

2. Move to root project directory
    ```sh
    cd 3rdpartysolution_demo
    ```

3. Copy ```.env``` file
    ```sh
    cp .env.example .env
    ```

4. Configure your ```.env``` file. Make sure your database name and smtp mailer set up correctly
    ```sh
    ...
    
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=yourdatabasename
    DB_USERNAME=root
    DB_PASSWORD=
    
    ...

5. From root project directory, run the following commands
     ```sh
    composer install
    ```
    ```sh
    php artisan serve
    ```
    
6. Run in your browser
    ```sh
    http://127.0.0.1:8000
    ```
7. **Enjoy!** :)

