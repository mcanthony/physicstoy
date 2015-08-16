p2.js physics editor for the web

# Install & build

Prerequisities: [Node.js](https://nodejs.org/), [Grunt](http://gruntjs.com/), [Heroku toolbelt](https://toolbelt.heroku.com/), [Postgres](http://www.postgresql.org/)

```
$ npm install && grunt
```

# Run the server

```
$ foreman start
```

# Sample .env file

The following environment variables are used in the app. You'll need to specify at least the ```DATABASE_URL``` to get the app to run at all.

```
DATABASE_URL=postgres://user@domain/postgres
PHYSICSTOY_GA_ID=UAXXXX
PHYSICSTOY_TITLE=PhysicsToy
PHYSICSTOY_MAX_DB_CONNECTIONS=10
PHYSICSTOY_MAX_CACHED_THUMBNAIL_PAGES=10
PHYSICSTOY_MAX_CACHED_SCENES=10
PHYSICSTOY_MAX_CACHE_AGE=0
```

# Contribute

PR's are very welcome! Base your PR's on the ```master``` branch. Thank you.
