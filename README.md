## Installer une application react sur Laravel 10

```
composer create-project laravel/laravel example-app     | Crée un projet laravel

composer require laravel/breeze --dev                   | Installe Breeze sur l'application

php artisan breeze:install react --dark                 | Installe React sur l'aplication Laravel avec le dark theme 

yarn                                                    |  Installe les packages nécessaire
```

### A faire lors d'un clone github : 
```
composer install                          | Installe tout les packages laravel 

yarn                                      | Installe tout les packages nodes 

créé le .env  --> php artisan migrate     |  Crée le env et migres tout sur la Base de Donner 
```


En production : yarn build 

En dévelopement : yarn dev (permet de charger a chaque modification)
