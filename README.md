Universal Analytics Koa - NodeJS
===

A fork of Peaks & Pies universal-analytics with added support for koa framework middleware.

## Usage

In order to make session-based apps easier to work with, `universal-analytics-koa` also provides a middleware that works in the koa request context.

```javascript
var ua  = require("universal-analytics");
var koa = require("koa");

var app = koa()

app.use(ua.koa("UA-XXXX-Y"));
```

The middleware will attach the `universal analytics` visitor instance to every request (`this.req.visitor`).

## In-Depth Documentation

[https://github.com/peaksandpies/universal-analytics](https://github.com/peaksandpies/universal-analytics)
