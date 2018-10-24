Todolist-example
================

Tasks CRUD with Mongo provider example using [restful-admin](https://github.com/gmenti/restful-admin)


Installation
------------

```shell
git clone https://github.com/gmenti/todolist-example.git
cd todolist-example
cp .env.example .env
composer install
```

Configuration
-------------
Open the .env file and change with your configuration.
```env
MONGO_URI=mongodb://localhost:3306
MONGO_DB=todolist
```

Commands
------------------------
Start application on [http://localhost:8000]()
```shell
composer run-script dev
```

API Doc
-------
https://documenter.getpostman.com/view/476481/RWgxtEsA