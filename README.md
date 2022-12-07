# Indicaciones generales paraprobar esta aplicacion
Para ejecutar este proyecto una vez clonado debes ejecutar el comando para instalar todas las dependencias y pueda ejecutar correctamente: 

```php
composer install
```

En caso de generar Error 500 al correr el archivo, ejecutar los siguientes comandos:

Después cambiar instalar composer, cambiar el nombre del .env.example por .env

```php
mv .env.example .env
```

limpiar cache
```php
php artisan cache:clear
composer dump-autoload
```

y por último generar el key
```php
php artisan key:generate
```

Ejecutar el proyecto
```php
php artisan serve
```

Puede encontrar este proyecto en [Examen-ISW811]()

## Contributors
[![](https://gitlab.com/uploads/-/system/user/avatar/1607844/avatar.png?width=400)](https://gitlab.com/FrancizHernandez)