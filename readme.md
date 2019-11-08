# PHP API

HTTP API backend service for managing two resources and their relations: subscribers and fields

## Installing

 1. Checkout the project
 2. Use Composer to install packages
 3. Rename .env.examplt to .env and set your MySQL configuration
 4. Run command from terminal:

```
php -S 127.0.0.1:8000 -t public
```

### Prerequisites

This project was developed using PHP 7.1, MySql 5.7 and Composer

### Client

There is a client that can be used to access API, check for the correct URL case you're running on a different machine than server.
Files to check under client:

```
fields.js
subscribers.js
subscribers_fields.js
```

## Running the tests

To run the PHPUnit Tests

```
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests/SubscriberTest
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests/FieldTest
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests/FieldSubscriberTest
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
