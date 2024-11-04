# Day 2 of PHP

## Conditionals

### If statements

`if` statements run certain code block based on conditions

```php
<?php

    $age = 30;

    if ($age == 30) {
        echo "Age is 30";
    }
?>
```

### if-else statements

`if-else` statements execute code based on conditions, and `else` allow addition of multiple different conditions

```php
<?php

    $age = 30;

    if ($age > 30) {
        echo "Age is greater than 30";
    } elseif ($age < 30) {
        echo "Age is less than 30";
    } else {
        echo "Age is equal to 30";
    }
?>
```
