# Serve a Static File

For a [Des Moines Web Geeks](http://www.dsmwebgeeks.com) event, I wanted to show different ways to store a simple HTML file.

You should be able to run each of the examples below in this folder to serve that static file:

### [http://localhost:3000](http://localhost:3000)

## PHP

```sh
$ php -t ./public -S localhost:3000
```

Dependencies:

- [PHP](http://php.net/)

## Python

```sh
$ cd public && python -m SimpleHTTPServer 3000
```

Dependencies:

- [Python](https://www.python.org/)

## NodeJS

```sh
$ npm install
$ npm start
```

Dependencies:

- [NodeJS](https://nodejs.org/)

## MAMP

1. Download and install [MAMP](https://www.mamp.info/en/)
1. In Settings, change the Apache home directory to `/public` within this folder
1. Visit [http://localhost:8888](http://localhost:8888)

## Web Browser

1. Open this folder in Finder/Explorer
1. Double click `public/index.html` or drag it into a web browser like Chrome

## Native Apache (Mac Only)

By default, Mac OSX comes with Apache installed.
