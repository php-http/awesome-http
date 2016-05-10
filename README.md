# Awesome HTTP

A curated list of amazingly awesome PHP libraries, resources and shiny things related to HTTP.

*(Inspired by [awesome-php](https://github.com/ziadoz/awesome-php#http))*

## Table of Contents

- [Awesome HTTP](#awesome-http)
    - [Client](#client)
    - [Message](#message)
    - [Middleware](#middleware)
    - [Middleware dispatcher](#middleware-dispatcher)
    - [Testing](#testing)

## Client
*HTTP Clients and adapters.*

- [Guzzle](http://guzzlephp.org)
- [Buzz](https://github.com/kriswallsmith/Buzz)
- [HTTPFul](https://github.com/nategood/httpful)
- [Requests](https://github.com/rmccue/Requests)
- [HTTPlug](http://httplug.io) - PSR-7 HTTP Client interface.
- [cURL client](https://github.com/php-http/curl-client)
- [Socket client](https://github.com/php-http/socket-client)
- [Guzzle 6 adapter](https://github.com/php-http/guzzle6-adapter) - HTTPlug adapter for Guzzle 6.
- [Guzzle 5 adapter](https://github.com/php-http/guzzle5-adapter) - HTTPlug adapter for Guzzle 5.
- [Buzz adapter](https://github.com/php-http/buzz-adapter) - HTTPlug adapter for Buzz.
- [React adapter](https://github.com/php-http/react-adapter) - HTTPlug adapter for React.


## Message
*HTTP Message (mostly PSR-7) related implementations.*

- [Guzzle PSR-7](https://github.com/guzzle/psr7) - PSR-7 HTTP Message implementation.
- [Zend Diactoros](https://github.com/zendframework/zend-diactoros) - PSR-7 HTTP Message implementation.
- [PHP HTTP Message](https://github.com/php-http/message) - PSR-7 Message extensions and tools.
- [PHP HTTP Message Factory](https://github.com/php-http/message-factory) - PSR-7 Message Factory interfaces.


## Middleware
*HTTP Middleware implementations.*

- [akrabat/rka-ip-address-middleware](https://github.com/akrabat/rka-ip-address-middleware)
- [akrabat/rka-scheme-and-host-detection-middleware](https://github.com/akrabat/rka-scheme-and-host-detection-middleware)
- [bear/middleware](https://github.com/bearsunday/BEAR.Middleware)
- [hannesvdvreken/psr7-middlewares](https://github.com/hannesvdvreken/psr7-middlewares)
- [los/api-problem](https://github.com/Lansoweb/api-problem)
- [los/los-rate-limit](https://github.com/Lansoweb/LosRateLimit)
- [monii/monii-action-handler-psr7-middleware](https://github.com/monii/monii-action-handler-psr7-middleware)
- [monii/monii-nikic-fast-route-psr7-middleware](https://github.com/monii/monii-nikic-fast-route-psr7-middleware)
- [monii/monii-response-assertion-psr7-middleware](https://github.com/monii/monii-response-assertion-psr7-middleware)
- [mtymek/blast-base-url](https://github.com/mtymek/blast-base-url)
- [ocramius/psr7-session](https://github.com/Ocramius/PSR7Session)
- [oscarotero/psr7-middlewares](https://github.com/oscarotero/psr7-middlewares)
- [php-middleware/block-robots](https://github.com/php-middleware/block-robots)
- [php-middleware/http-authentication](https://github.com/php-middleware/http-authentication)
- [php-middleware/log-http-messages](https://github.com/php-middleware/log-http-messages)
- [php-middleware/maintenance](https://github.com/php-middleware/maintenance)
- [php-middleware/phpdebugbar](https://github.com/php-middleware/phpdebugbar)
- [php-middleware/request-id](https://github.com/php-middleware/request-id)
- [relay/middleware](https://github.com/relayphp/Relay.Middleware)


## Middleware dispatcher
*HTTP Middleware builders/dispatchers/applications.*

- [Adroit](https://github.com/bitExpert/adroit)
- [Glue](https://github.com/madewithlove/glue)
- [Middleman](https://github.com/mindplay-dk/middleman)
- [Relay](https://github.com/relayphp/Relay.Relay)
- [Slim](https://github.com/slimphp/Slim)
- [Zend Expressive](https://github.com/zendframework/zend-expressive)
- [Zend Stratigility](https://github.com/zendframework/zend-stratigility)


## Testing
*HTTP related testing tools.*

- [PHP VCR](http://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
- [PSR-7 Assertions](https://github.com/Maks3w/Psr7Assertions) - PSR-7 conformance test helpers.
- [PSR-7 Assertions](https://github.com/martin-helmich/phpunit-psr7-assert) - PSR-7 assertions for testing PSR-7 usage.
