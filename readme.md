## Baseado no Tutorial
[Link Tutorial](https://www.flynsarmy.com/2015/02/creating-a-basic-todo-application-in-laravel-5-part-1/)

Comandos usados neste tutorial
>laravel new laravel-todo
ou 
>composer create-project laravel/laravel laravel-todo 5.0 --prefer-dist
>cd laravel-todo
>php artisan migrate:status
>php artisan make:migration create_projects_and_tasks_tables --create=“projects
>composer dump-autoload
>php artisan db:seed
>php artisan make:model Project
>php artisan make:model Task
>php artisan tinker
  > App\Project::count();
  > App\Task::count();
>php artisan make:controller ProjectsController
>php artisan make:controller TasksController
>php artisan route:list

## Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/downloads.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, queueing, and caching.

Laravel is accessible, yet powerful, providing powerful tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## Official Documentation

Documentation for the framework can be found on the [Laravel website](http://laravel.com/docs).

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
