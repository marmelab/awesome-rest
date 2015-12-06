# Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

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
  * [Java](#java)
* [Testing](#testing)
  * [Querying](#querying)
  * [Mocking](#mocking)
  * [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
* [Documentation](#documentation)
* [SaaS Tools](#saas-tools)
* [Miscellaneous](#miscellaneous)



## Design

* [Architectural Styles and
the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) by the famous Martin Fowler
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) - Clear explanation on what HATEOAS is, and why you should use it.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)

## Standards

* [JSON API](http://jsonapi.org/) - Standard for building APIs in JSON.
* [RAML](http://raml.org/) - Simple and succinct way to describe RESTful API.
* [JSend](http://labs.omniti.com/labs/jsend) - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
* [OData](http://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [HAL](http://stateless.co/hal_specification.html) - Simple format that gives a consistent and easy way to hyperlink between resources in your API (see: [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
* [Hydra](http://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
* [Schema.org](http://schema.org) - Collection of schemas describing common data models.

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services.
* [Buzz](https://github.com/kriswallsmith/buzz) - Another lightweight HTTP client.
* [unirest for PHP](https://github.com/Mashape/unirest-php) - Simplified, lightweight HTTP client library.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) - AngularJS service to handle REST API properly and easily.
* [restful.js](https://github.com/marmelab/restful.js) - JS client for interacting with server-side RESTful resources.
* [traverson](https://github.com/basti1302/traverson) - A Hypermedia API/HATEOAS Client for Node.js and the Browser

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) - REST client library for node.js.
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - Simplified, lightweight HTTP client library.

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [Spyke](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner.
* [excon](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - Serve a fully RESTful API directly from an existing PostgreSQL database.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.

### Node.js

* [node-restify](https://github.com/restify/node-restify) - Framework specifically meant for REST API.
* [Sails.js](http://sailsjs.org/) - Node.js Web framework embedding a command to generate automatically a REST API.
* [mers](https://github.com/jspears/mers) - Express service exposing Mongoose finders as RESTful API.
* [Baucis](https://github.com/wprl/baucis) - Build scalable REST API based on your Mongoose entities.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) - Isomorphic Resource engine for JavaScript.
* [loopback](http://loopback.io/) - Powerful Node.js framework for creating APIs and easily connecting to backend data sources.
* [Feathers](http://feathersjs.com/) - is a real-time, micro-service web framework that gives you control over your data via RESTful resources, sockets and flexible plug-ins.

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - Micro-web application providing a REST API on top of any relational database.
* [Negotiation](https://github.com/willdurand/Negotiation) - Content negotiation library.
* [Drest](https://github.com/leedavis81/drest) - Library for exposing Doctrine entities as REST resource endpoints.
* [Restler](https://github.com/Luracast/Restler) - Lightweight framework to expose PHP methods as RESTful web API.
* [HAL](https://github.com/blongden/hal) - Hypertext Application Language (HAL) builder library.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - API builder built with Zend Framework 2.
* [phprest](https://github.com/phprest/phprest) - Specialized REST microframework for PHP.
* [Hateoas](https://github.com/willdurand/Hateoas) - PHP library to support implementing representations for HATEOAS REST web services.
* [PHP Schema](http://php-schema.dunglas.com) - Generator of PHP data model using schemas from Schema.org.

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - Complete guide to build a state-of-the-art REST API with Symfony2 framework.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - Bundle handling view, routing, error handling, etc. for your REST API.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - Build a REST API based on Doctrine entities using conventions over configuration.
* [lakion/Lionframe](http://lakion.com/lionframe) - Glu between several community libraries to ease API development.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - Integrate the [Hateoas](https://github.com/willdurand/Hateoas) library into a Symfony2 application.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - Start with a Symfony2 application with all REST-friendly bundles pre-configured.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - Boostrap ng-admin configuration based on `stanlemon/rest-bundle`.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - Build a REST API which follow Hydra/JSON-LD specification.
* [API Platform](https://github.com/api-platform/api-platform) - Specialize Symfony edition for the creation of hypermedia REST APIs.

### Python

* [Django REST framework](http://www.django-rest-framework.org/) - Powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* [flask-restful](http://flask-restful.readthedocs.org/) - Extension for Flask that adds support for quickly building REST APIs.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
* [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.
* [restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
* [savory-pie](https://github.com/RueLaLa/savory-pie/) - REST API building library (django, and others).

### Ruby

* [Grape](http://intridea.github.io/grape/) - Opinionated micro-framework for creating REST-like APIs in Ruby.

### Go

* [gocrud](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Thin layer on top of `net/http` that helps building RESTful APIs easily.
* [sleepy](https://github.com/dougblack/sleepy) - RESTful micro-framework written in Go.
* [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [go-restful](https://github.com/emicklei/go-restful) - A declarative highly readable framework for building restful API's.
* [Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [Zerver](https://github.com/cosiner/zerver) - Zerver is a expressive, modular, feature completed RESTful framework.

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) - Netty-based, highly performant, lightweight, container-less, plugin-extensible, framework that is ideal for microservice architectures.

## Testing

### Querying

* [httpie](https://github.com/jkbrzt/httpie) - Command line HTTP client, far more dev-friendly than `curl`.
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - Chrome extension essential to test manually REST API.
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines (bash or zsh).
* [jq](https://github.com/stedolan/jq) - Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
* [HttpMaster](http://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.
* [Paw (HTTP & REST client)](https://luckymarmot.com/paw) - Native HTTP client on Mac to test REST APIs. Supports Basic Auth, OAuth 1 / 2, imports Swagger and API Blueprint definitions.

### Mocking

* [FakeRest](https://github.com/marmelab/FakeRest) - Patch XMLHttpRequest to fake a REST API client-side.
* [json-server](https://github.com/typicode/json-server) - Serve a REST API from fixture files using quick prototyping.
* [Mocky.io](http://www.mocky.io/) - Free online service to create fake HTTP responses.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - Mock RESTful API based on swagger schema

### Public REST APIs To Use In Tests

* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - The world's largest API repository.
* [Public APIS](https://www.publicapis.com/) - Explore The Largest API Directory In The Galaxy.
* [Marvel Comics API](http://developer.marvel.com/) - Query characters, stories, events about Marvel superheroes.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - Free online REST service that you can use whenever you need some fake data.

## Documentation 

* [Swagger](http://swagger.io/) - Documentation/querying web interface for REST APIs.
* [API doc](http://apidocjs.com/) - Inline Documentation for RESTful web APIs.

## SaaS tools

* [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
* [import.io Magic](https://magic.import.io/) - Create a REST API from any website in one click.
* [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
* [Apigee](https://apigee.com) - Apigee is the leading provider of API technology and services for enterprises and developers.


## Miscellaneous

* [ng-admin](https://github.com/marmelab/ng-admin) - Add an AngularJS admin GUI to any RESTful API.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
