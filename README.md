<p align="center">
<a href="http://laravel-admin.org/">
<img src="http://laravel-admin.org/img/logo004.png" alt="laravel-admin">
</a>
 
<p align="center">dsaga<code>laravel-admin</code> is administrative interface builder for laravel which can help you build CRUD backends just with few lines of code.</p>

<p align="center">
<a href="http://laravel-admin.org/docs">Documentation</a> | 
<a href="http://laravel-admin.org/docs/#/zh/">中文文档</a> | 
<a href="http://laravel-admin.org/demo">Demo</a> | 
<a href="https://github.com/z-song/laravel-admin.org">Demo source code</a> | 
<a href="https://github.com/laravel-admin-extensions">Extensions</a>
</p>

<p align="center">
    <a href="https://travis-ci.org/z-song/laravel-admin">
        <img src="https://travis-ci.org/z-song/laravel-admin.svg?branch=master" alt="Build Status">
    </a>
    <a href="https://styleci.io/repos/48796179">
        <img src="https://styleci.io/repos/48796179/shield" alt="StyleCI">
    </a>
    <a href="https://scrutinizer-ci.com/g/z-song/laravel-admin/?branch=master">
        <img src="https://scrutinizer-ci.com/g/z-song/laravel-admin/badges/quality-score.png?b=master" alt="Scrutinizer Code Quality">
    </a>
    <a href="https://packagist.org/packages/dsaga/laravel-admin">
        <img src="https://img.shields.io/packagist/l/dsaga/laravel-admin.svg?maxAge=2592000&&style=flat-square" alt="Packagist">
    </a>
    <a href="https://packagist.org/packages/dsaga/laravel-admin">
        <img src="https://img.shields.io/packagist/dt/dsaga/laravel-admin.svg?style=flat-square" alt="Total Downloads">
    </a>
    <a href="https://github.com/z-song/laravel-admin">
        <img src="https://img.shields.io/badge/Awesome-Laravel-brightgreen.svg?style=flat-square" alt="Awesome Laravel">
    </a>
</div>

<p align="center">
    Inspired by <a href="https://github.com/sleeping-owl/admin" target="_blank">SleepingOwlAdmin</a> and <a href="https://github.com/zofe/rapyd-laravel" target="_blank">rapyd-laravel</a>.
</p>

Screenshots
------------

![laravel-admin](https://cloud.githubusercontent.com/assets/1479100/19625297/3b3deb64-9947-11e6-807c-cffa999004be.jpg)

Requirements
------------
 - PHP >= 7.0.0
 - Laravel >= 5.5.0
 - Fileinfo PHP Extension
 
Installation
------------

> This package requires PHP 7+ and Laravel 5.5, for old versions please refer to [1.4](http://laravel-admin.org/docs/v1.4/#/) 

First, install laravel 5.5, and make sure that the database connection settings are correct.

```
composer require dsaga/laravel-admin
```

Then run these commands to publish assets and config：

```
php artisan vendor:publish --provider="Dsaga\Admin\AdminServiceProvider"
```
After run command you can find config file in `config/admin.php`, in this file you can change the install directory,db connection or table names.

At last run following command to finish install. 
```
php artisan admin:install
```

Open `http://localhost/admin/` in browser,use username `admin` and password `admin` to login.

Configurations
------------
The file `config/admin.php` contains an array of configurations, you can find the default configurations in there.

Backers
------------

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/laravel-admin#backer)]

<a href="https://opencollective.com/laravel-admin#backers" target="_blank"><img src="https://opencollective.com/laravel-admin/backers.svg?width=890"></a>

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/laravel-admin#sponsor)]

<a href="https://opencollective.com/laravel-admin/sponsor/0/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/1/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/2/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/3/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/4/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/5/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/6/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/7/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/8/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/laravel-admin/sponsor/9/website" target="_blank"><img src="https://opencollective.com/laravel-admin/sponsor/9/avatar.svg"></a>

Other
------------
`laravel-admin` based on following plugins or services:

+ [Laravel](https://laravel.com/)
+ [AdminLTE](https://almsaeedstudio.com/)
+ [Datetimepicker](http://eonasdan.github.io/bootstrap-datetimepicker/)
+ [font-awesome](http://fontawesome.io)
+ [moment](http://momentjs.com/)
+ [Google map](https://www.google.com/maps)
+ [Tencent map](http://lbs.qq.com/)
+ [bootstrap-fileinput](https://github.com/kartik-v/bootstrap-fileinput)
+ [jquery-pjax](https://github.com/defunkt/jquery-pjax)
+ [Nestable](http://dbushell.github.io/Nestable/)
+ [toastr](http://codeseven.github.io/toastr/)
+ [X-editable](http://github.com/vitalets/x-editable)
+ [bootstrap-number-input](https://github.com/wpic/bootstrap-number-input)
+ [fontawesome-iconpicker](https://github.com/itsjavi/fontawesome-iconpicker)

License
------------
`laravel-admin` is licensed under [The MIT License (MIT)](LICENSE).
