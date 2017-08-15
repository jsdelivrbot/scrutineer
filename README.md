# scrutineer
[![Heroku](http://heroku-badge.herokuapp.com/?app=scrutineer&svg=1)](https://scrutineer.herokuapp.com)
[![Build Status](https://travis-ci.org/zuzak/scrutineer.svg?branch=master)](https://travis-ci.org/zuzak/scrutineer)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1f2b7c213b34470db18e7e59b133a894)](https://www.codacy.com/app/douglas/scrutineer)

## Screenshots
![Screenshot of Questionnaire](https://i.imgur.com/605GZBsl.png)

![Screenshot of Council detail](https://i.imgur.com/xVyafxal.jpg)

![Screenshot of Station detail](https://i.imgur.com/00cSkTpl.png)
## Setup

## Requirements
* MongoDB (defaults to `mongodb://localhost/scrutineer`: override it with the `MONGODB_URI` environment variable)

By default we synchronise with upstream data sources. Set the `NO_SYNC` environment variable (to something) to disable this.