Yii Numero Letras
=================
Convierte un número a letras

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist inquid/yii-en-letras "*"
```

or add

```
"inquid/yii-en-letras": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php

        $letras = NumeroALetras::convertir(12345);
```        
Si deseas convertir un número con decimales y mostrar la moneda:
```php
        $letras = NumeroALetras::convertir(12345.67, 'colones', 'centimos');
```

Lo cual te devuelve: *DOCE MIL TRESCIENTOS CUARENTA Y CINCO COLONES CON SESENTA Y SIETE CENTIMOS*

## Créditos

Basado en https://github.com/arielcr/numero-a-letras
