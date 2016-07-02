# NO-MVC

_Sometimes you don't need MVC_

<br>

NO-MVC framework is a solution for building small-medium sized applications without having to enforce MVC architecture and at the same time being able to utilize some of the goodies common in MVC frameworks such as routing, separated public folder, clean folder structure, etc..

This project is a WiP. Documentation is not ready.
<br>

**Features:**
* Routing (AltoRouter)
* Templates (Twig)
* Database access helper (Aura.Sql based on PDO)
* Caching
* Improved security by separating the document root directory
* Plenty of common useful functions
* Fast and lightweight (Core framework size is under **100 KB**)

Using PhpStorm 2016+ by JetBrains you will experience near **PERFECT**  intellisense thanks to the PHP 7 type hinting and consideration in the code base

**Requirements:**
* PHP 7.0+
* Ability to change document root of your web server
* Ability to redirect all non static requests to `wwwroot/index.php` (`.htaccess` and `web.config` files are already included)

**Important Note:**

You must set your web server's document root to `wwwroot` folder!


Author: Vahid Amiri Motlagh (http://atvsg.com) - 2016