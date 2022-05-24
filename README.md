## Introduction to e-commerce systems

This online trading platform is supported by Laravel 5.4. version is being developed.

## Server performance

	PHP >= 5.6.4
	MySQL >= 5.7
	OpenSSL PHP Extension
	PDO PHP Extension
	Mbstring PHP Extension
	Tokenizer PHP Extension
	XML PHP Extension


<a name="installation"></a>
## Install

Run the following command to clone this project:

```
git clone https://github.com/tortuvshin/ecommerce.git
```

Composer download and install

```
[Composer pull](https://getcomposer.org/download/)
```

Next, go to the downloaded folder and run the composer update / install command

```
composer install
```

Nodejs download and install

```
https://nodejs.org/en/download/
```

NPM Download directories
```
npm install
```

## Adjust

Then change the .env-example file to .env and configure your database and server

After creating and configuring the database, create the tables with the following command:

```
php artisan migrate
```

Enter the test data with the following command:

```
php artisan db:seed
```
	
```
php artisan key:generate
```
	
Enter directories related to frontend development with the following command:

```
bower install
```

Get the reChaptcha code:

```
https://www.google.com/recaptcha/admin#list
```

```
RECAPTCHA_PUBLIC_KEY, and RECAPTCHA_PRIVATE_KEY
```

Insert the reCaptcha code into the .env file. For example:

```
RECAPTCHA_PUBLIC_KEY = ModuRecaptchaPublicKeyObtained

RECAPTCHA_PRIVATE_KEY = ModuRecaptchaPrivateKeyObtained
```

*** Note: *** `` `APP_DEBUG == true``` or do not use reCaptcha when debug is on



Install NPM directories:

```
npm install 
```

If you are developing using the Window operating system and VM, run the following command:
```
npm install --no-bin-links
```

Laravel Mix use

```
npm run dev
```

Test user information

	Username: admin@admin.com
	Password: admin


[NODEJS]: https://nodejs.org/en/download/
[COMPOSER]: https://getcomposer.org/download/
[RECAPTCHA]: https://www.google.com/recaptcha/admin#list
