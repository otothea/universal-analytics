Universal Analytics Koa - NodeJS
===

A fork of Peaks & Pies [universal-analytics](https://github.com/peaksandpies/universal-analytics) with added support for koa framework middleware.

## Usage

```javascript
var ua  = require("universal-analytics");
var koa = require("koa");

var app = koa()

app.use(ua.koa("UA-XXXX-Y"));
```

The middleware will attach the `visitor` instance to every request (`this.req.visitor`).

## The Rest of the Documentation

[https://github.com/peaksandpies/universal-analytics](https://github.com/peaksandpies/universal-analytics)
