# Cameron's Bakery

Welcome to the Cameron's Bakery website! It includes such great features as a welcome page and a pastry quiz! There is a sub-theme and a basic custom theme built with the intention of learning how to theme in Drupal 7.

## Prerequisites

You will need one of the following server management programs properly installed on your computer.

* [MAMP](https://www.mamp.info/en/)
* [WAMP](http://www.wampserver.com/en/)
* [LAMP](https://www.apachefriends.org/index.html)

## Installation

**Step 1**: Clone this repository to your local computer

```console
git clone https://github.com/katharynreed/cameron_bakery
```

**Step 2**: Using your server management software, import the `bakery.sql.zip` file from `/sites/db-backup`

**Step 3**: Create a new user on the database using username: 'cameron' and password: 'cameron'; you can double check in sites/default/settings.php

**Step 4**: Ensure that your web server software's document root is set to the project's root directory and that the MySQL port is set to 8889

**Step 5**: Visit the app at [http://localhost:8889](http://localhost:8889).

## License

MIT License. Copyright 2017 Katharyn Reed
