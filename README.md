## Instrucciones

Para el despliegue del proyecto se deben seguir las sigueintes instrucciones.
- Clonar el repositorio: *git clone https://github.com/Francisco734/capi_examen_back_FRANCISCO_SANCHEZ.git*
- Dirigirse a la carpeta del proyecto: */capi_examen_back_FRANCISCO_SANCHEZ*
- Instalar las dependencias y paquetes necesarios: *composer install*
- En el archivo *.env* cambiar las credenciales de conexión a la base de datos
- Limpiar cache: *php artisan optimize:clear*
- Ejecutar una migración: *php artisan migrate*
- Correr los seeders: *php artisan db:seed --class 'Database\Seeders\UserSeeder'*
- Levantar la palicación: *php artisan serve*

## EndPoint
/api/users
