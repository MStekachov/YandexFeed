yandex-feed
===========
Yandex feed-generator

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist mistek/yii2-yandex-feed "*"
```

or add

```
"mistek/yii2-yandex-feed": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \mistek\feed\YandexFeed::widget(); ?>```