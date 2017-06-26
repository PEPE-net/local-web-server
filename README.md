[![npm (tag)](https://img.shields.io/npm/v/local-web-server/next.svg)](https://www.npmjs.org/package/local-web-server)
[![npm module downloads](https://img.shields.io/npm/dt/local-web-server.svg)](https://www.npmjs.org/package/local-web-server)
[![Build Status](https://travis-ci.org/lwsjs/local-web-server.svg?branch=next)](https://travis-ci.org/lwsjs/local-web-server)
[![Dependency Status](https://david-dm.org/lwsjs/local-web-server/next.svg)](https://david-dm.org/lwsjs/local-web-server/next)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](https://github.com/feross/standard)
[![Join the chat at https://gitter.im/lwsjs/local-web-server](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lwsjs/local-web-server?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**This documentation is a work in progress**

# local-web-server

The modular development web server for productive front-end and full-stack engineers. Use this tool to:

* Help build a web application using any architecture (static website, Single Page Application with client-side rendering, dynamic app with server-side rendering, Progressive Web App etc.)
* Prototype a web service (REST API, microservice, websocket server application etc)

Agnostic which front-end framework (React, Polymer, Angular etc) you use, if any.

## Synopsis

This package installs the `ws` command-line tool. The most simple use case is to run `ws` without any arguments - this will host the current directory as a static web site.

```sh
$ ws
Serving at http://mbp.local:8000, http://127.0.0.1:8000, http://192.168.0.100:8000
```

Being modular and extensible, there are many possibilites how to use this tool for more advanced usage.

## Install

Requires node v7.6 or higher. Install the [previous release](https://github.com/lwsjs/local-web-server/tree/v1.x) for node >= v4.0.0. 

```sh
$ npm install -g local-web-server@next
```
* * *

&copy; 2013-17 Lloyd Brookes <75pound@gmail.com>. Documented by [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown).
