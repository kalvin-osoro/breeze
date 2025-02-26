<p align="center"><img src="/art/logo.svg" alt="Logo Laravel Breeze"></p>

<p align="center">
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/dt/laravel/breeze" alt="Total Downloads">
    </a>
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/v/laravel/breeze" alt="Latest Stable Version">
    </a>
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/l/laravel/breeze" alt="License">
    </a>
</p>

## Introduction

Breeze provides a minimal and simple starting point for building a Laravel application with authentication. Styled with Tailwind, Breeze publishes authentication controllers and views to your application that can be easily customized based on your own application's needs.

Laravel Breeze is powered by Blade and Tailwind. If you're looking for a more robust Laravel starter kit that includes two factor authentication, Livewire / Inertia support, and more, check out [Laravel Jetstream](https://jetstream.laravel.com).

## Official Documentation

Documentation for Breeze can be found on the [Laravel website](https://laravel.com/docs/starter-kits#laravel-breeze).

## Contributing

Thank you for considering contributing to Breeze! You can read the contribution guide [here](.github/CONTRIBUTING.md).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

Please review [our security policy](https://github.com/laravel/breeze/security/policy) on how to report security vulnerabilities.

## License

Laravel Breeze is open-sourced software licensed under the [MIT license](LICENSE.md).


#Notes

. Install the Library e.g chart.js

npm install chart.js


. compile the chart.js library to use it in a blade file

. Import the Library in a Blade Template
e.g., resources/views/layouts/app.blade.php

 then use the library a your JavaScript code

 const ctx = document.getElementById('myChart').getContext('2d');

Create a route and controller:

php artisan make:controller DataVisualizationController

. Define a method,to handle the data visualization page:

public function index()
{
    return view('data-visualization');
}

. define a route to access the data visualization page:

Route::get('/data-visualization', 'DataVisualizationController@index');


Create a view for data visualization and add html structure for it


then test the app


