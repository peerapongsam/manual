# PHP


### Version
```php
<?php
phpinfo();
?>
```

```bash
php -v
```


### Mysqli
```php
<?php
$con = mysqli_connect('localhost', 'root', '', 'test');
$sql = 'SELECT * FROM user';
$result = mysqli_query($con, $sql);
mysqli_close($con);
```
