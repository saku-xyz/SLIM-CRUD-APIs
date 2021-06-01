# SLIM-CRUD RESTful API

This is a RESTful api built with the SlimPHP framework and uses MySQL for storage.

### Version
1.0.0

### Usage


### Installation

1. Clone the repo

2. Create database or import from _sql/slimapp.sql

3. Edit db/config params

4. Install SlimPHP and dependencies

```sh
$ composer install
```
### API Endpints
```sh
$ GET /api/customers
$ GET /api/customer/{id}
$ POST /api/customer/add
$ PUT /api/customer/update/{id}
$ DELETE /api/customer/delete/{id}
```
