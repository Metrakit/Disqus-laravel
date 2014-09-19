Disqus-laravel
==============

Disqus library for Laravel 4

This package is available on Packagist:
https://packagist.org/packages/metrakit/disqus-laravel

And on Packalyst:
http://packalyst.com/packages/package/metrakit/disqus-laravel

##How to install

- Add the package to your composer.json:

    ```json
"metrakit/disqus-laravel": "dev-master"
    ```
    
- Use the command : 
```
composer update
```

- Add this line to the "app.php" file in the config folder where is the "provider" category :
    ```php 
// Disqus library
Metrakit\Disqus\DisqusServiceProvider',
    ```
- Add this line to the "app.php" file in the config folder where is the "aliases" category :    
    ```php 
// Disqus library
'Disqus'          => 'Disqus\Disqus',
    ```
    
##Credits

The Disqus team :
https://github.com/disqus/disqus-php
