# Awesome REST

This is a link repository centralizing resources, tools and frameworks about REST architecture. Feel free to contribute to this ongoing list.

## Designing

* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/): a full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Haters gonna HATEOAS](http://timelessrepo.com/haters-gonna-hateoas): a clear explanation on what HATEOAS is, and why you should use it.
* [RAML](http://raml.org/): a simple and succinct way to describe RESTful API

## Building

### JavaScript

* [restangular](https://github.com/mgonto/restangular): AngularJS service to handle REST API properly and easily
* [restful.js](https://github.com/marmelab/restful.js): a JS client for interacting with server-side RESTful resources

### Node.js

* [Baucis](https://github.com/wprl/baucis): build scalable REST API based on your Mongoose entities
* [node-restify](https://github.com/mcavage/node-restify): a framework specifically meant for REST API
* [mers](https://github.com/jspears/mers): an Express service to expose Mongoose finders as RESTful API
* [Sails.js](http://sailsjs.org/): a Node.js Web framework embedding a command to generate automatically a REST API

### PHP

* [phprest](https://github.com/phprest/phprest): specialized REST microframework for PHP
* [Hateoas](https://github.com/willdurand/Hateoas): a PHP library to support implementing representations for HATEOAS REST web services
* [Microrest](https://github.com/marmelab/microrest.php): a micro-web application providing a REST API on top of any relational database

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/): a complete guide to build a state-of-the-art REST API with Symfony2 framework
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle): bundle handling view, routing, error handling, etc. for your REST API
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle): build a REST API based on Doctrine entities using conventions over configuration
* [Lionframe](http://lakion.com/lionframe): a glu between several community libraries to ease API development
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle): integrate the [Hateoas](https://github.com/willdurand/Hateoas) library into a Symfony2 application
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition): start with a Symfony2 application with all REST-friendly bundles pre-configured

### Go

* [go-json-rest](https://github.com/ant0ine/go-json-rest): a thin layer on top of `net/http` that helps building RESTufmigl API easily

## Testing

* [httpie](https://github.com/jakubroztocil/httpie): a command line HTTP client, far more dev-friendly than `curl`
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm): a Chrome extension essential to test manually REST API
* [FakeRest](https://github.com/marmelab/FakeRest): patch XMLHttpRequest to fake a REST API client-side
* [json-server](https://github.com/typicode/json-server): serve a REST API from fixture files using quick prototyping
* [resty](https://github.com/micha/resty): little command line REST client that you can use in pipelines (bash or zsh)

## REST based-tools

* [postgrest](https://github.com/begriffs/postgrest): serve a fully RESTful API directly from an existing PSQL database
* [ng-admin](https://github.com/marmelab/ng-admin): add an AngularJS admin GUI to any RESTful API