JIRA REST APIs
==============
This is the reference for the Jira Cloud REST API.
This API is the primary way to interact with Jira remotely, whether you are building an app, scripting interactions 
with Jira or developing any other integration. This page documents the REST resources available in Jira Cloud, 
along with expected HTTP response codes and sample requests.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist richweber/yii2-jira "*"
```

or add

```
"richweber/yii2-jira": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \richweber\jira\AutoloadExample::widget(); ?>```