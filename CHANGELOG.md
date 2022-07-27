## 4.0.1 2022-07-27 <dave at tiredofit dot ca>

   ### Added
      - Support updated tiredofit/nginx and tiredofit/nginx-php-fpm images
      - Dynamically create Crontabs
      - Set additional missing defaults
      - General cleanup of code


## 4.0.0 2021-10-06 <dave at tiredofit dot ca>

   ### Added
      - Refactor Image to support latest base container updates

## 3.51 2018-08-19 <dave at redacted>

* Repair Permissions for /www/moodle

## 3.5 2018-06-10 <dave at redacted>

* Add Graphviz 
* Add Aspell

## 3.41 2017-12-11 <dave at redacted>

* Remove Cron Email Script to not blast our email providers

## 3.4 2017-11-30 <dave at redacted>

* Switch to Moodle edge
* Use Alpine Edge as a Base
* Texlive Included

## 3.3 2017-07-06 <dave at redacted>

* Added PHP_TIMEOUT

## 3.2 2017-07-04 <dave at redacted>

* Added TexLive and Glibc

## 3.1 2017-07-03 <dave at redacted>

* Fix S6 Issues and add logrotate

## 3.0 2017-07-01 <dave at redacted>

* Rebase from nginx-php-fpm 5.6 with s6
* Added email apk
* 

## 2.1 2017-04-12 <dave at redacted>

* Rebase - Alpine 3.5
* Moodle 2.9.9
* Php5.6-FPM

## 2.0 2017-02-21 <dave at redacted>

* Update to support Zabbix Monitoring

## 1.1 2017-01-26 <dave at redacted>

* Rework to Build in Reverse and SSL Proxy Support
* Pull this repository and update the run.sh and edit the commented field to support downloading a new version (presently it is using 3.2, but it can use 3.1)

## 1.0 2017-01-03 <dave at redacted>

* Alpine:edge
* PHP7
* PHP Composer