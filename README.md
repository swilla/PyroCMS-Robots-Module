# PyroCMS Robots Module

This module was created by [Jacob Albert (Jaap) Jolman](http://www.odin-ict.nl/).

These days search engines like to read a robots.txt from your website. but when you have alot of website it starts to get really anoying to keep track of them. well here is the solution. this module will output the robots.txt for you.

## Installation

Copy robots/ to your addons/SITE_REF/modules or addons/shared_addons/modules folder.

Add the following Route:

```
$route['robots.txt'] = 'robots/index';
```