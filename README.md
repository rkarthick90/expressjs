Express provides a minimal interface to build our applications. It provides us the tools that are required to build our app. It is flexible as there are numerous modules available on npm, which can be directly plugged into Express.


```js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

## Why Express

Unlike its competitors like Rails and Django, which have an opinionated way of building applications, Express has no "best way" to do something. It is very flexible and pluggable.

## Features

  * Robust routing
  * Focus on high performance
  * Super-high test coverage
  * HTTP helpers (redirection, caching, etc)
  * View system supporting 14+ template engines
  * Content negotiation
  * Executable for generating applications quickly

## Frameworks built on Express

Several popular Node.js frameworks are built on Express:

* Feathers: Build prototypes in minutes and production ready real-time apps in days.
* ItemsAPI: Search backend for web and mobile applications built on Express and Elasticsearch.
* KeystoneJS: Website and API Application Framework / CMS with an auto-generated React.js Admin UI.
* Kraken: Secure and scalable layer that extends Express by providing structure and convention.
* LEAN-STACK: The Pure JavaScript Stack.
* LoopBack: Highly-extensible, open-source Node.js framework for quickly creating dynamic end-to-end REST APIs.
* MEAN: Opinionated fullstack JavaScript framework that simplifies and accelerates web application development.
* Sails: MVC framework for Node.js for building practical, production-ready apps.
* Bottr: Framework that simplifies building chatbot applications.
* Hydra-Express: Hydra-Express is a light-weight library which facilitates building Node.js Microservices using ExpressJS.
* Blueprint: Highly-configurable MVC framework for composing production-ready services from reusable components
* Locomotive: Powerful MVC web framework for Node.js from the maker of Passport.js
* graphql-yoga: Fully-featured, yet simple and lightweight GraphQL server

##pug

Pug (earlier known as Jade) is a terse language for writing HTML templates.

* Produces HTML
* Supports dynamic code
* Supports reusability (DRY)
* It is one of the most popular template language used with Express.

To understand Pug, you need to remember that the browser reads HTML and CSS and then displays formatted images and text to the client based on what that HTML and CSS tells it to do.

Pug is the middleman.

Pug is a template engine for Node.js.

A template engine allows us to inject data and then produce HTML.

In short: At run time, Pug (and other template engines) replace variables in our file with actual values, and then send the resulting HTML string to the client.
