# Localidades y Provincias de Argentina para Laravel >= 5.4

Este paquete crea las migraciones y tablas de paises, provincias y localidades.

También genera un comando para popular estás bases.

# Insctrucciones

```
composer require cardumen/argentina-provincias-localidades:1.1
```


Agregar el provider en config/app 

```
Cardumen\ArgentinaProvinciasLocalidades\ArgentinaProvinciasLocalidades::class,
```

Correr las migraciones

```
php artisan migrate
```

Cargar los datos

```
php artisan provincias-localidades:cargar
```

Destacar

```
php artisan provincias-localidades:destacar 
```

Quitar destaque

```
php artisan provincias-localidades:cargar --quitar
```


#   a r g e n t i n a - p r o v i n c i a s - l o c a l i d a d e s  
 