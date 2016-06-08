# Demo of testing Swagger Web API with Gauge JS

**Status: Incomplete**

This demo tests a dummy NodeJS-based Web API written with Swagger with [Gauge][_gauge], using the [JavaScript][_gaugejs] language runner.

## Setting up

* Install [Gauge][_gauge].
* Install [NodeJS][_node].
* Install Swagger: `$ sudo npm install -g swagger`

## Running Gauge tests

* `$ npm start`: Start the Swagger API server.
* `$ npm test`: While the server is running, run Gauge tests (in another terminal).

[_gauge]: http://getgauge.io
[_gaugejs]: https://github.com/getgauge-contrib/gauge-js
[_node]: https://nodejs.org
