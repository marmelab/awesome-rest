# Awesome REST

A collaborative list of great resources about RESTful API architecture, development, test, and performance. Feel free to contribute to this on-going list.

* [Design](#design)
* [Standards](#standards)
* [Clients](#clients)
  * [PHP](#php-clients)
  * [Client-side JavaScript](#javascript-clients)
  * [Node.js](#nodejs-clients)
  * [Ruby](#ruby-clients)
  * [Go](#go-clients)
* [Servers](#servers)
  * [Directly On Top Of A RMDB](#directly-on-top-of-a-rmdb)
  * [Node.js](#nodejs)
  * [PHP](#php)
  * [Symfony2](#symfony2)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
* [Testing](#testing)
  * [Querying](#querying)
  * [Mocking](#mocking)
  * [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
* [Documentation](#documentation)
* [SaaS Tools](#saas-tools)
* [Miscellaneous](#miscellaneous)



## Design

* [Architectural Styles and
the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST.
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - a full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) by the famous Martin Fowler
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) - a clear explanation on what HATEOAS is, and why you should use it.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)

## Standards

* [JSON API](http://jsonapi.org/) - a standard for building APIs in JSON
* [RAML](http://raml.org/) - a simple and succinct way to describe RESTful API
* [JSend](http://labs.omniti.com/labs/jsend) - a simple specification that lays down some rules for how JSON responses from web servers should be formatted
* [OData](http://www.odata.org/) - an open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [HAL](http://stateless.co/hal_specification.html) - a simple format that gives a consistent and easy way to hyperlink between resources in your API (see: [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - a standard to describe Linked Data and hypermedia relations in JSON (W3C)
* [Hydra](http://www.hydra-cg.com/) - a vocabulary for Hypermedia-Driven Web APIs (W3C)
* [Schema.org](http://schema.org) - a collection of schemas describing common data models

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services
* [Buzz](https://github.com/kriswallsmith/buzz) - another lightweight HTTP client
* [unirest for PHP](https://github.com/Mashape/unirest-php) - Simplified, lightweight HTTP client library

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) - AngularJS service to handle REST API properly and easily
* [restful.js](https://github.com/marmelab/restful.js) - a JS client for interacting with server-side RESTful resources

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) - REST client library for node.js
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - Simplified, lightweight HTTP client library

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [Spyke](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner.
* [excon](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - serve a fully RESTful API directly from an existing PostgreSQL database
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - A simple REST-like / CRUD server for any MySQL database

### Node.js

* [node-restify](https://github.com/mcavage/node-restify) - a framework specifically meant for REST API
* [Sails.js](http://sailsjs.org/) - a Node.js Web framework embedding a command to generate automatically a REST API
* [mers](https://github.com/jspears/mers) - an Express service to expose Mongoose finders as RESTful API
* [Baucis](https://github.com/wprl/baucis) - build scalable REST API based on your Mongoose entities
* [flatiron/resourceful](https://github.com/flatiron/resourceful) - an isomorphic Resource engine for JavaScript
* [loopback](http://loopback.io/) - powerful Node.js framework for creating APIs and easily connecting to backend data sources

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - a micro-web application providing a REST API on top of any relational database
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
* [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
* [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2.
* [phprest](https://github.com/phprest/phprest) - specialized REST microframework for PHP
* [Hateoas](https://github.com/willdurand/Hateoas) - a PHP library to support implementing representations for HATEOAS REST web services
* [PHP Schema](http://php-schema.dunglas.com) - a generator of PHP data model using schemas from Schema.org

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - a complete guide to build a state-of-the-art REST API with Symfony2 framework
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - bundle handling view, routing, error handling, etc. for your REST API
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - build a REST API based on Doctrine entities using conventions over configuration
* [lakion/Lionframe](http://lakion.com/lionframe) - a glu between several community libraries to ease API development
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - integrate the [Hateoas](https://github.com/willdurand/Hateoas) library into a Symfony2 application
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - start with a Symfony2 application with all REST-friendly bundles pre-configured
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - boostrap ng-admin configuration based on `stanlemon/rest-bundle`
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - build a REST API which follow Hydra/JSON-LD specification
* [API Platform](https://github.com/dunglas/api-platform) - a Symfony edition specialized in the creation of hypermedia REST APIs

### Python

* [Django REST framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* [flask-restful](http://flask-restful.readthedocs.org/) - An extension for Flask that adds support for quickly building REST APIs.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - A Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
* [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.
* [restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
* [savory-pie](https://github.com/RueLaLa/savory-pie/) - REST API building library (django, and others)

### Ruby

* [Grape](http://intridea.github.io/grape) - An opinionated micro-framework for creating REST-like APIs in Ruby.

### Go

* [go-json-rest](https://github.com/ant0ine/go-json-rest) - a thin layer on top of `net/http` that helps building RESTufmigl API easily
* [sleepy](https://github.com/dougblack/sleepy) - a RESTful micro-framework written in Go
* [restit](https://github.com/yookoala/restit) - A Go micro framework to help writing RESTful API integration test
* [go-relax](https://github.com/codehack/go-relax) - A framework of pluggable components to build RESTful API's
* [go-rest](https://github.com/ungerik/go-rest) - A small and evil REST framework for Go
* [Goat](https://github.com/bahlo/goat) - A minimalistic REST API server in Go
* [Resoursea](https://github.com/resoursea/api) - A REST framework for quickly writing resource based services.
* [Zerver](https://github.com/cosiner/zerver) - Zerver is a expressive, modular, feature completed RESTful framework.

## Testing

### Querying

* [httpie](https://github.com/jakubroztocil/httpie) - a command line HTTP client, far more dev-friendly than `curl`
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - a Chrome extension essential to test manually REST API
* [resty](https://github.com/micha/resty) - little command line REST client that you can use in pipelines (bash or zsh)
* [jq](https://github.com/stedolan/jq) - command line JSON processor, to use in combination with a command-line HTTP client like cURL

### Mocking

* [FakeRest](https://github.com/marmelab/FakeRest) - patch XMLHttpRequest to fake a REST API client-side
* [json-server](https://github.com/typicode/json-server) - serve a REST API from fixture files using quick prototyping
* [Mocky.io](http://www.mocky.io/) - free online service to create fake HTTP responses 

### Public REST APIs To Use In Tests

* [Public APIS](https://www.publicapis.com/) - Explore The Largest API Directory In The Galaxy
* [Marvel Comics API](http://developer.marvel.com/) - query characters, stories, events about Marvel superheroes
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - a free online REST service that you can use whenever you need some fake data.

## Documentation 

* [Swagger](http://swagger.io/) - Documentation/querying web interface for REST APIs
* [API doc](http://apidocjs.com/) - Inline Documentation for RESTful web APIs

## SaaS tools

* [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing
* [import.io Magic](https://magic.import.io/) - Create a REST API from any website in one click
* [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.

## Miscellaneous

* [ng-admin](https://github.com/marmelab/ng-admin) - add an AngularJS admin GUI to any RESTful API
* [Build APIs You Won't Hate](http://apisyouwonthate.com/) - Ebook about planning, implementing, and testing your API.
