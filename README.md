
![](https://github.com/kubi-codes/cisetup/blob/master/assets/img/kubicode_logo.png)


![](https://img.shields.io/github/stars/kubi-codes/cisetup) ![](https://img.shields.io/github/forks/kubi-codes/cisetup) ![](https://img.shields.io/github/tag/kubi-codes/cisetup) ![](https://img.shields.io/github/release/kubi-codes/cisetup) ![](https://img.shields.io/github/issues/pandaokubi-codes/cisetup)

Is a codeigniter 3 framework that has been modified and added new features such as dotenv, sweet alert 2 & bootstrap 4

## Installation

Use the composer to install cisetup.

```bash
composer create-project kubi/cisetup
```
## Some additional features

#### XSS Echo Filter
```php
<?php echos($foobar); ?>
```

#### Assets Url
```php
<img src="<?= asset_url() . 'img/foobar.png' ?>">
```

#### Create & Call dotenv

```dotenv
APP_TIMEZONE=Asia/Jakarta
```
```dotenv
getenv('APP_TIMEZONE');
```

#### Use Sweet Alert

```php
 notif('type','title', 'message','url');    
```
* **type** = (**'success'**,**'warning'**,**'info'**,**'danger'**)
* **url** = **base_url()**+**url**

example
```php
 notif('success','Login Success', 'Welcome to app','home/user');    
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Thanks For
* [agungjk](https://github.com/agungjk/phpdotenv-for-codeigniter)
* [Codeigniter](https://github.com/bcit-ci/CodeIgniter)
* [Bootstrap 4](https://github.com/twbs/bootstrap)
* [Sweet Alert 2](https://github.com/sweetalert2/sweetalert2)

## License
[MIT](https://choosealicense.com/licenses/mit/)
