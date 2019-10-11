# This repository has moved to [https://github.com/holidayapi/php-holidayapi](https://github.com/holidayapi/php-holidayapi)

**The PHP package has also been renamed from `joshtronic/php-holidayapi` to `holidayapi/holidayapi-php`**

**This repository has been archived.**

---

# php-holidayapi

Official PHP library for [Holiday API](https://holidayapi.com)

## Installation

```shell
composer require "joshtronic/php-holidayapi:dev-master"
```

## Usage

```php
$hapi = new HolidayAPI\v1('_YOUR_API_KEY_');

$parameters = array(
  // Required
  'country' => 'US',
  'year'    => 2016,
  // Optional
  // 'month'    => 7,
  // 'day'      => 4,
  // 'previous' => true,
  // 'upcoming' => true,
  // 'public'   => true,
  // 'pretty'   => true,
);

$response = $hapi->holidays($parameters);
```
