# Day 1 of PHP

## Setup
To be able to use and build apps in PHP, The language has to be installed, some database, a web server and probably many other tools which all work together.

Best way to get those is to install some packages which has all those and will be configured.
- Xampp
- Lamp
- Wamp
- Laragon
- Laravel Herd

I personally recommend downloading **Laragon** or **Laravel Herd** as it seems like its easier to use and understand.

## About PHP
PHP is a language which is used for Web development especially in the backend.
It is used by Wordpress and it is used by more than 60% of the websites.

PHP code runs in a `.php` file.

## Syntax
PHP file starts with the following tag `<?php` and ends with `?>`:

```php
<?php
 // code
?>
```

### Comments
```php
<?php
    // single line comment


    /* multi-
     line
     comment
    */

?>
```

### Print/Echo to browser 
```php
<?php
    echo "Hello, World!";
    print 'Hello, you!';
?>
```

### Variables
Variables in PHP start with $ sign:

```php
<?php

 $name = "Adnan";
 $age = 30;

 echo "Name: $name, Age: $age";
?>
```

### Data Types
1. String

```php
<?php
    // String can be in double or single quotes
    $hello = "Hello, this is a string";

    $goodnight = 'Goodnighty';
?>
```

2. Integer
```php
<?php

    $num10 = 10;
    $numX = 999;
    $numY = 192813;

?>
```

3. Float

```php
<?php

    $float10 = 10.00;
    $floatX = 999.99;
    $floatY = 192813.324;

?>
```

4. Boolean

```php
<?php

    $true = true;
    $false = false;
    
?>
```

5. Array
```php
<?php
    // Array can contain multiple items and types

    $nameArray = ['Adnan', 'Jack', 'Sparrow'];

    $numArray = [12, 34, 5433];

    $mixArr = ["Hello", 12, true, 2434.433];
?>
```

6. Objects
```php
<?php
    
    class Person {
        public $name;
        public function __construct($name) {
            $this->name = $name;
        }
    }
    $person = new Person("Alice");

?>
```

7. Null
```php
<?php

    $empty_variable = null;

?>
```

This wraps up the first day of learning PHP. 