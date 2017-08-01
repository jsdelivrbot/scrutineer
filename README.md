# scrutineer
[![Heroku](http://heroku-badge.herokuapp.com/?app=scrutineer&svg=1)](https://scrutineer.herokuapp.com)
[![Build Status](https://travis-ci.org/zuzak/scrutineer.svg?branch=master)](https://travis-ci.org/zuzak/scrutineer)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Requirements
* MongoDB (defaults to `mongodb://localhost/scrutineer`: override it with the `MONGODB_URI` environment variable)

By default we synchronise with upstream data sources. Set the `NO_SYNC` environment variable (to something) to disable this.