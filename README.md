# jodel-web [![Build Status](https://scrutinizer-ci.com/g/mmainstreet/jodel-web/badges/build.png?b=master)](https://scrutinizer-ci.com/g/mmainstreet/jodel-web/build-status/master) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/mmainstreet/jodel-web/issues)


## Setting up jodel-web ##
1. Create MySql Database
2. Edit config/config-sample.ini.php and insert MySQL login credentials
3. Create Jodel account (see below)
4. Done


## How to Use##
### Create Jodel account ###
Run
``` PHP
createAccount();
```
on index.php


## Requirements ##
+ Web server (tested on Apache/2.4.18 (Ubuntu))
+ PHP 7.0 (tested on 7.0.8-3)
 * for random_int()
+ MySQL (tested on 5.7.16-0)
+ jQuery (tested on 2.0.2 (already included)) 

### Optional ###
+ HTTPS (deactivate by deleting .htaccess)

### Tanks to [LauretBernd](https://github.com/LauertBernd) and [Christian Fibich](https://bitbucket.org/cfib90/)###

### [![HitCount](https://hitt.herokuapp.com/mmainstreet/jodel-web.svg)](https://github.com/mmainstreet/jodel-web)
