# redis-broadcaster
Redis broadcaster to push message to redis using php

Installation
------------
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist mifta/redis-broadcaster
```

or add

```
"mifta/redis-broadcaster": "dev-master"
```

to the require section of your composer.json.

Usage
-----
```
use mifta\RedisBroadcaster;

$broadcaster = new RedisBroadcaster();
$broadcaster->broadcast($payload);
```
