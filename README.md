# PHP-Socks5-Server
SOCKS5 server with php

## Usage

```php
<?php // example.php

include_once __DIR__.'/vendor/autoload.php';

$server = new \Aaurizon\ProxyServer\Socks5Server();

$server->run();
```

```bash
$ php example.php
```
