# PHP Conditional Statements
_if...else statement_ dapat digunakan untuk mengeksekusi kondisi tertentu. Misalkan suatu kondisi dikatakan benar maka melakukan suatu aksi dan jika salah maka melakukan aksi yang lain.
## if statement
_if statement_ hanya mengeksekusi suatu kondisi yang bernilai benar.
```php
<?php
  //initial variable
  $var1 = 30;
  $var2 = 20;

  if ($var1 + $var2 == 50) {
    echo "true";
  }
 ?>
 ```
 $var1 dan $var2 merupakan variabel. Karena kondisi pernyataan _if_ di atas benar dan hanya berlaku jika kondisinya benar, maka kondisi tersebut dijalankan.
 ## if...else statement
 _if...else statement_ digunakan untuk mengeksekusi 2 kondisi benar dan salah.
 ```php
 <?php

  $var1 = 45;
  $var2 = 15;

  if ($var1 * $var2 == 675) {
    echo "true";
  } else {
    echo "false";
  }

 ?>
 ```
 ## if...elseif...else statement
 _if...elseif...else statement_ digunakan untuk mengeksekusi lebih dari 2 kondisi.
 ```php
 <?php

  $var1 = 49;
  $var2 = 45;

  if ($var1 >=50 && $var2 <50) {
    echo "true";
  } elseif ($var1 >=50 || $var2 <50) {
    echo "something";
  } else {
    echo "false";
  }

 ?>
```
## switch statement
```php
<?php

  $varN = array("pink","green","red");

  switch ($varN) {

    case $varN["0"]=="green":
      echo "Im green";
      break;

    case $varN["1"]=="blue";
      echo "Im blue";
      break;

    case $varN["2"]=="red":
      echo "yes, Im red";
      break;

    default:
    echo "no conditions are executed!";
      break;
  }

 ?>
```
