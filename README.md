Node.js Stuff
=============

A continuously expanded list of Node.js libs I want to keep in mind.

* [Node Version Manager](#node-version-manager)
* [Development Tools](#development-tools)
* [Process Manager](#process-manager)
* [ORM's & ODM's](#orms--odms)
* [File Based Databases](#file-based-databases)
* [Command Line](#command-line)
* [Scraper & Crawler](#scraper--crawler)
* [Data Parser/Converter](#data-parserconverter)
* [Fake Data & Mocking](#fake-data--mocking)
* [Geo & Mapping](#geo--mapping)
* [Authentication](#authentication)
* [Validation](#validation)
* [Security](#security)
* [Headless Browser](#headless-browser)
* [Internationalization](#internationalization)
* [General](#general)

### Node Version Manager
- [n](https://github.com/tj/n) - Version management
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node
- [nvm](https://github.com/creationix/nvm) - Bash script to manage multiple versions

### Development Tools
- [iron-node](http://s-a.github.io/iron-node/index.html) - Debug Node.js code with Chrome Developer Tools
- [nodemon](https://github.com/remy/nodemon) - Monitor for any changes in your application and restart the server
- [node-dev](https://github.com/fgnass/node-dev) - Zero-conf reloading
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools
- [node-supervisor](https://github.com/isaacs/node-supervisor) - Supervisor script that runs your code, watches for changes and reloads your application
- [theseus](https://github.com/adobe-research/theseus) - A debugger for Brackets

### Web Application Frameworks
- [adonisjs](http://www.adonisjs.com/) - ES6 friendly MVC Framework
- [deployd](http://deployd.com/) - Toolkit for building realtime APIs
- [sails](http://sailsjs.org/) - MVC framework with auto-generated REST APIs, Web-Socket support and security policies
- [strapi](http://strapi.io/) - Framework with admin panel, user management and GraphQL support
- [trails](https://github.com/trailsjs/trails) - Framework with API-driven design philosophy

### Process Manager
- [forever](https://github.com/foreverjs/forever) - CLI tool for ensuring that a given script runs continuously
- [naught](https://github.com/andrewrk/naught) - Zero downtime deployment
- [PM2](https://github.com/Unitech/pm2) - Process manager for with a built-in load balancer

### ORM's & ODM's
- [bookshelf](http://bookshelfjs.org/) - ORM for PostgreSQL, MySQL, and SQLite
- [graffiti](https://github.com/RisingStack/graffiti) - GraphQL ORM
- [jugglingdb](https://github.com/1602/jugglingdb) - ORM/ODM for Redis, Mongo, MySQL, SQLite, PostgreSQL, neo4j and memory
- [mongoose](http://mongoosejs.com/) - ODM for Mongo
- [mongorito](https://github.com/vdemedes/mongorito) - ES6 generator-based MongoDB ODM
- [moron.js](https://github.com/Vincit/moron.js) - Based on knex supporting SQLite3, Postgres and MySQL
- [node-orm2](https://github.com/dresende/node-orm2) - ORM for MySQL, MariaDB, PostgreSQL, Amazon Redshift and SQLite
- [sequelize](http://docs.sequelizejs.com/en/latest/) - ORM for PostgreSQL, MySQL, MariaDB, SQLite and MSSQL
- [thinky](https://github.com/neumino/thinky) - Rethink ORM
- [waterline](https://github.com/balderdashy/waterline) - ORM/ODM for MySQL, Mongo, PostgreSQL, Redis and more

### File Based Databases
- [diskdb](https://github.com/arvindr21/diskDB) - A Lightweight Disk based JSON Database with a MongoDB like API
- [lowdb](https://github.com/typicode/lowdb) - Flat JSON file database (Lo-Dash functional programming API)
- [nedb](https://github.com/louischatriot/nedb) - Embedded datastore (Mongo API)

### Command Line
- [blessed](https://github.com/chjj/blessed) - High-level widgets for the Terminal
- [blessed-contrib](https://github.com/yaronn/blessed-contrib) - Terminal dashboards using ascii/ansi
- [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling helper
- [Clor](https://github.com/bucaran/clor) - Civilized terminal styles
- [cmnd](https://github.com/keithwhor/cmnd) - Command Line Interface Utility using ES6 idioms
- [colors](https://github.com/marak/colors.js/) - Get colors in your console
- [Commander](https://github.com/visionmedia/commander.js) - Command-line interfaces made easy
- [Inquirer](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces
- [minimist](https://github.com/substack/minimist) - Parse argument options
- [vantage](https://github.com/dthree/vantage) - An interactive CLI for Node
- [vorpal](https://github.com/dthree/vorpal) - Framework for interactive CLI apps.
- [yargs](https://github.com/bcoe/yargs) - Optstrings parser

### Scraper & Crawler
- [crawler](https://github.com/sylvinus/node-crawler) - Web Crawler/Spider + server-side jQuery
- [ineed](https://github.com/inikulin/ineed) - Web scraping and HTML-reprocessing
- [noodlejs](http://noodlejs.com/) - Server and module for querying and scraping data from web documents
- [node-osmosis](https://github.com/rc0x03/node-osmosis) - HTML/XML parser and web scraper for NodeJS
- [scrape-it](https://github.com/IonicaBizau/scrape-it) - A scraping module for humans
- [skrap](https://github.com/nickdima/skrap) - Easily scrap web pages by providing json recipes
- [SUq](https://github.com/MattMcFarland/SUq) - Scraping Utility
- [x-ray](https://github.com/lapwinglabs/x-ray) - See through the <html> noise
- [yakuza](https://github.com/Narzerus/yakuza) - Highly scalable scraping framework

### Data Parser/Converter
- [any-json](https://github.com/laktak/any-json) - Convert csv, xls, xlsx, xml, yaml and more to JSON
- [BabyParse](https://github.com/Rich-Harris/BabyParse) - CSV parser based on PapaParse
- [dsv](https://github.com/mbostock/dsv) - A parser and formatter for DSV (CSV and TSV) files
- [exceljs](https://github.com/guyonroche/exceljs) - Excel Workbook Manager
- [node-csv](https://github.com/wdavidw/node-csv) - Full featured CSV parser

### Fake Data & Mocking
- [chance](http://chancejs.com) - Minimalist generator of random strings, numbers and more
- [faker](https://github.com/marak/Faker.js/) - Generate massive amounts of fake data
- [fake identity](https://github.com/travishorn/fake-identity) - Generate random identity objects including name, address, etc
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations library

### Geo & Mapping
- [Leaflet headless](https://github.com/jieter/leaflet-headless) - Headless version of Leaflet using jsdom and canvas
- [mapshaper](https://github.com/mbloch/mapshaper) - Tools for editing geospatial vector data
- [node-gdal](https://github.com/naturalatlas/node-gdal) - GDAL bindings
- [ogr2ogr](https://github.com/wavded/ogr2ogr) - ogr2ogr wrapper
- [tilestream](https://github.com/mapbox/tilestream) - A map tile server powered by MBTiles files
- [tilestrata](https://github.com/naturalatlas/tilestrata) - A pluggable map tile server
- [turf](https://github.com/Turfjs/turf) - A modular geospatial engine
- [Windshaft](https://github.com/CartoDB/Windshaft) - A map tile server for PostGIS based on Mapnik

### Authentication
- [darklord](https://github.com/GrumpyWizards/DarkLord) - Stateless Authentication Server - JWT based authentication
- [drywall](https://github.com/jedireza/drywall/) - A website and user system
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, facebook, & more)
- [frame](https://github.com/jedireza/frame) - A user system API based on hapi
- [node-oauth2-server](https://github.com/thomseddon/node-oauth2-server) - Complete, compliant and well tested module for implementing an OAuth2 Server/Provider
- [passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication
- [passwordless](https://github.com/florianheinemann/passwordless) - Module to authenticate users without password

### Validation
- [is.js](https://github.com/arasatasaygin/is.js) - Micro check library
- [joi](https://github.com/hapijs/joi) - Object schema validation
- [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization

### Security
- [Credential](https://github.com/ericelliott/credential) - Password hashing and verification
- [CSRF](http://www.senchalabs.org/connect/csrf.html) - CSRF protection middleware
- [Helmet](https://github.com/helmetjs/helmet) - Middleware to help secure your Express/Connect apps
- [NodeSecurity](https://github.com/nodesecurity) - The Node Security Project

### Headless Browser
- [casperjs](http://casperjs.org/) - Navigation scripting & testing utility for PhantomJS and SlimerJS
- [nightmarejs](http://www.nightmarejs.org/) - A high level wrapper for Phantomjs
- [phantomjs](http://phantomjs.org/) - Headless WebKit scriptable with a JavaScript API
- [slimerjs](http://slimerjs.org/) - Scriptable browser based on Gecko

### Internationalization
- [i18n](https://github.com/mashpie/i18n-node) - Lightweight simple translation module
- [i18n-abide](https://github.com/mozilla/i18n-abide) - connect module for i18n and l10n support
- [Jed](https://github.com/SlexAxton/Jed) - Gettext Style i18n
- [messageformat](https://github.com/SlexAxton/messageformat.js) - MessageFormat for Javascript - i18n Plural and Gender Capable Messages
- [polyglot.js](https://github.com/airbnb/polyglot.js) - Give your JavaScript the ability to speak many languages

### General
- [cheerio](https://github.com/cheeriojs/cheerio) - Implementation of core jQuery for the server
- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs
- [fortune](http://fortunejs.com) - A framework for prototyping hypermedia APIs
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the fs object
