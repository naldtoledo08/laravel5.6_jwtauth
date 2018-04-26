
## Laravel 5.6 - JWT Authentication

Basic Implementation of JWT Authentication in Laravel 5.6. Please check the tutorial below

```
- [Laravel JWT Authentication Tutorial](https://appdividend.com/2018/02/24/laravel-jwt-authentication-tutorial/).
```

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 


### Prerequisites

composer


### Installation

Clone the repository below
```
https://github.com/naldtoledo08/laravel5.6_jwtauth.git
```

Run `composer install`

Generate App key by running `php artisan key:generate`

Create `.env` file and update your db credentials

Run `php artisan migrate`


## Running the tests

Submit/Post user credentials, *email, name, passoword* for registration of Account on `/public/api/user/register`

Then login, Post your *email, passowrd* on `/public/api/user/login`. Notice that it will return a token you can use for accessing the site. Please save it on local storage on anywhere you like and used it for accessing end point urls.

Accessing page sample. GET `/public/api/users`, use Header Authorization: Bearer {token}


