### Siga o Tutorial
[Faça esta aplicação em 5 pequenas partes](https://www.flynsarmy.com/2015/02/creating-a-basic-todo-application-in-laravel-5-part-1/)

Comandos do terminal usados neste tutorial

laravel new laravel-todo

ou

composer create-project laravel/laravel laravel-todo 5.0 --prefer-dist

-------
cd laravel-todo

php artisan migrate:status

php artisan make:migration create_projects_and_tasks_tables --create=“projects

composer dump-autoload

php artisan db:seed

php artisan make:model Project

php artisan make:model Task

    php artisan tinker
     App\Project::count();
     App\Task::count();

php artisan make:controller ProjectsController

php artisan make:controller TasksController

php artisan route:list

--------

## Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/downloads.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel é um framework web em PHP, gratuito, com rápido aprendizado, estruturado, modularizado, independente, reaproveitável. Possui autenticação, rotas, sessão, fila e cache. Trabalha com scripts de banco para atualização das modificações ocorridas durante o desenvolvimento e o framework ainda pode trabalhar com testes unitários (TDD).


## Documentação oficial

Visite [Laravel website](http://laravel.com/docs).
Visite também [Laravel BR](http://laravel.com.br)
Faça parte de uma comunidade [Laravel BR Slack](http://laravel-br.slack.com)

