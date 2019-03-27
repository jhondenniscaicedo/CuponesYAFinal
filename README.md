# CuponesYAFinal
Proyecto final, Ingeniería de software III

Para montar la base de datos:
1. Acceder a localhost/phpmyadmin
2. Crear una base dedatos llamada "cuponesya" con codificación "utf8_general_ci"
3. Desde una terminal acceder a la carpeta del proyecto
4. Ejecutar el comando: "php artisan migrate:refresh"
5. Acceder a la carpeta "database/migrations" y borrar el archivo llamado "2014_10_12_000000_create_users_table"
6. Ejecutar el comando "php artisan migrate:refresh --seed"
