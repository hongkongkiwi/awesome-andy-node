# Awesome Andy Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/gilbarbara/logos/e7b1dc2666c3dabe6c1276abd0a767b6ebd6af43/logos/nodejs-icon.svg" align="right" width="70">](https://nodejs.org)

> Andys curated list of delightful Node.js [packages](#packages) and [resources](#resources). ✨

## Packages

### Mad Science!

- [Mosca](https://github.com/mcollina/mosca) - Node.js MQTT Broker
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.
- [Shaman](https://github.com/nanopack/shaman) - Node.js API DNS
- [Etcd](https://github.com/coreos/etcd) - Highly-available key-value store for shared configuration and service discovery.
- [crtauth](https://github.com/spotify/crtauth) - A public key backed client/server authentication system
- [vault](https://www.vaultproject.io/)- Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing.
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.
- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables.
- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms.
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals.
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.


### Express

- [compression](https://github.com/expressjs/compression) - Gzip Compression for Express Middleware
- [helmet](https://www.npmjs.com/package/helmet) - Security Best Practices Middleware (adds/removes headers)
- [express-limiter](https://www.npmjs.com/package/express-limiter) - Rate limiting for express routes
- [express-crypto](https://github.com/mwiesmueller/express-crypto) - Request/Response Encryption/Decryption for express
- [http2-node](https://webapplog.com/http2-node) - HTTP/2 for Node
- [greenlock-express](https://www.npmjs.com/package/greenlock-express) - On demand SSL certificates for Express using LetsEncrypt


### Mongoose

- [mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) - Encryption and Authentication for mongoose fields
- [cachegoose](https://www.npmjs.com/package/cachegoose) - Caching for Mongoose which works the way you expect.
- [mongoose-type-email](https://www.npmjs.com/package/mongoose-type-email) - Email type for mongoose
- [mongoose-type-url](https://www.npmjs.com/package/mongoose-type-url) - URL type for mongoose
- [mongoose-type-uuid2](https://www.npmjs.com/package/mongoose-uuid2) - UUID2 type for mongoose
- [mongoose-type-bignumber](https://www.npmjs.com/package/mongoose-bignumber) - Bignumber type for mongoose
- [mongoose-type-imei](https://www.npmjs.com/package/mongoose-imei) - IMEI type for mongoose
- [mongoose-type-iban](https://www.npmjs.com/package/mongoose-iban) - IBAN type, for international banking account number mainly used in Europe
- [mongoose-type-html](https://www.npmjs.com/package/mongoose-type-html) - HTML type can also sanitize
- [mongoose-events-event-logger](https://www.npmjs.com/package/mongoose-events-event-logger) - Mongoose event logger
- [mongoose-i18n-neutral](https://www.npmjs.com/package/mongoose-i18n-neutral) - Storing text in different languages
- [mongoose-virtual-populate](https://www.npmjs.com/package/mongoose-virtual-populate) - Mongoose Virtual Populate
- [mongoose-plugin-autoinc](https://github.com/nodkz/mongoose-plugin-autoinc) - Mongoose auto incrementing fields
- [mongoose-aggregate-paginate](https://github.com/Maheshkumar-Kakade/mongoose-aggregate-paginate) - Mongoose Aggregation Pagination
- [mongoose-elasticsearch-xp](https://github.com/jbdemonte/mongoose-elasticsearch-xp) - Using ElasticSearch & Mongo together!
- [mongoose-transactions](https://github.com/daton89-topperblues/mongoose-transactions) - Transaction support for Mongoose (clustering operations)
- [mongoose-patch-histor](https://github.com/codepunkt/mongoose-patch-history) - Add Mongoose Patch capability
- [mongoose-intl-phone-number](https://github.com/Dashride/mongoose-intl-phone-number) - Mongoose International Phone Number Parsing
- [mongoose-subscriptions](https://github.com/enhancv/mongoose-subscriptions) - mongoose subscriptions (user & subscription billing). Syncs with Braintree for the payments side.

### FeathersJS

- [feathers-stripe](https://github.com/feathersjs-ecosystem/feathers-stripe) A stripe payment adapter for feathersjs
- [feathers-authentication-management](https://github.com/feathers-plus/feathers-authentication-management/blob/master/docs.md#database)
- [feathers-authentication-publickey](https://www.npmjs.com/package/feathers-authentication-publickey)
- [feathers-sync](https://github.com/feathersjs-ecosystem/feathers-sync)
- [feathers-hooks-rediscache](https://github.com/idealley/feathers-hooks-rediscache)
- [feathers-blob](https://github.com/feathersjs-ecosystem/feathers-blob) - Blob storage with a customizable backend (e.g. Amazon S3)
- [feathers-swagger](https://github.com/feathersjs-ecosystem/feathers-swagger) - Swagger Documentation for your API
- [feathers-authentication-hooks](https://github.com/feathersjs-ecosystem/feathers-authentication-hooks) - Some authentication hooks to take inspiration from
- [feathers-hooks-validate-joi](https://github.com/eddyystop/feathers-hooks-validate-joi) - Validation in Feathers Hooks using Joi
- [feathers-postmark](https://www.npmjs.com/package/feathers-postmark) - Feathers Postmark Service
- [feathers-authentication-ldap](https://www.npmjs.com/package/feathers-authentication-ldap) - Feathers Authentication Stratergy using LDAPA
- [feathers-distribute](https://www.npmjs.com/package/@kalisio/feathers-distributed) - A way to run distributed feathers servers with all calls syncronised
- [feathers-mocha-utils](https://www.npmjs.com/package/feathers-mocha-utils) - Feathers Server testing using Mocha
- [feathers-plus-graphql](https://www.npmjs.com/package/@feathers-plus/graphql) - GraphQL for feathers
- [feathers-authentication-popups](https://www.npmjs.com/package/feathers-authentication-popups) - Functions for handling OAUTH pop windows (e.g. Google Login)
- [feathers-logger](https://www.npmjs.com/package/feathers-logger) - Nice wrapper so you can do app.log
- [feathers-errors](https://www.npmjs.com/package/@feathersjs/errors) - Feathers error classes
