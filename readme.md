# Newsletter subscription with Mailchimp

So imagine that you want to subscribe your website visitors to your newsletter or you are starting a brand new product/service and you want to collect email address of anyone that is interested so that you can send them an email when it is published or any other scenario where you would want to collect visitor emails for a purpose of later sending them an email.

In this lesson I will show you how to create a free [Mailchimp](http://mailchimp.com/) account, create a list for newsletter subscribers and use Laravel to create a subscribe form for that list.

## Installation

Clone repository to your drive and type in terminal there:

```
composer install
```

## Configuration

Copy file `.env.example` to `.env` file:

```
cp .env.example .env
```

and change the `APP_KEY` in `.env` using:

```
php artisan key:generate
```

## Running

From terminal type:

```
php artisan serve
```

You should get an address to open in your browser like http://localhost:8000.

**Have fun!**