## Compile php
```
./buildconf

./configure --disable-all

make
```

## Write a php script with € instead of $ at the beginning of variables
```php
<?php // euro.php

€maVar = "Hello";

echo €maVar, "\n";

## Run it
sapi/cli/php euro.php
