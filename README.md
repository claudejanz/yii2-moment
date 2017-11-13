Yii2 Moment
=================

An simple Asset loader to load moment.js [website](https://momentjs.com/)

[![Latest Stable Version](https://poser.pugx.org/claudejanz/yii2-moment/v/stable)](https://packagist.org/packages/claudejanz/yii2-moment) [![Total Downloads](https://poser.pugx.org/claudejanz/yii2-moment/downloads)](https://packagist.org/packages/claudejanz/yii2-moment) [![Latest Unstable Version](https://poser.pugx.org/claudejanz/yii2-moment/v/unstable)](https://packagist.org/packages/claudejanz/yii2-moment) [![License](https://poser.pugx.org/claudejanz/yii2-moment/license)](https://packagist.org/packages/claudejanz/yii2-moment)


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist claudejanz/yii2-moment "*"
```

or add

```
"claudejanz/yii2-moment": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your view by:

```php
use claudejanz\yii2moment\MomentAsset
MomentAsset::register($this->view);
```