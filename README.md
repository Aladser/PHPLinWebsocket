# Вебсокет для PHP для Linux

## Настройка запуска в Laravel

+ *App\Http\Kernel.php:*

``` 
    protected $middleware = [
        ..,
        \App\Http\Middleware\IsActiveWebsocket::class,
    ];
```
+ *composer.json*

```
    "require": {
        "cboden/ratchet": "^0.4.4",
        "ratchet/pawl": "^0.4.1"
    },

        "autoload": {
        "psr-4": {
            "Aladser\\": "aladser/",
        }
    },
    ```
