# Easy3DCoin-PHP
A simple class for making calls to 3DCoin's API using PHP.

**1- Getting Started**

Include Easy3DCoin.php into your PHP script:

```
require_once('Easy3DCoin.php');
```


**2- Initialize 3DCoin connection/object:**

```
$Easy3DCoin = new Easy3DCoin('http://username:password@127.0.0.1:port/');
```


**3- Make calls to 3dcoind as methods for your object. Examples:**


```
$Easy3DCoin->getinfo();

$Easy3DCoin->getrawtransaction('5d3d6a8b935580b5d81c8435393fc5ac79b9aa63cd8dfb0d11b9a14e663b568d',1);

$Easy3DCoin->getblock('0000000000041b31a14d2571744e5c6c4373a920d1aaa2dc4766c86294ce2cfc');
```
