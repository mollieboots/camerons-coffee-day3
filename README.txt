# _**Cameron's Coffee**_
#### _**By Mollie Bootsma**_
---
## Description

_Drupal 7 project for Cameron's Coffee Shop._

_This site was built using [Drupal 7.43](https://www.drupal.org/drupal-7.43-release-notes)._

___
## Installation/Setup

### Prerequisites

_You will need the following things properly installed on your computer._

* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/)
* [MAMP](https://www.mamp.info/en/)

## Installation

* `git clone https://github.com/MBAllely/bookstore.git`
* change into the new directory
* `echo export PATH="$HOME/.composer/vendor/bin:$PATH" >> ~/.bash_profile`
* Start up mamp and point servers to main directory
* Go to localhost:8888/phpmyadmin in browser and import `bookstore.sql.zip` DB found in bookstore/sites/DB-Backup
* Create DB username `cameron` with password `password`
* Go to localhost:8888 to view Drupal project.

## Databases Used
* `bookstore`

## Usernames and Passwords
* DB: `cameron:password`
* Drupal site maintenance account: `admin:admin`

## Running / Development

* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

### License

MIT License.

Copyright (c) 2016 **_Mollie Bootsma_**
