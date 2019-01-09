![](https://img.shields.io/packagist/dt/thelegendarymarc/php-ogparser.svg) 
Open Graph Parser  
======================  
  
This is a very very simple PHP open graph parser.   
  
It's Fork from <https://github.com/mapkyca/php-ogp>  
  
Usage  
-----  
  
Install with Composer  ``composer require thelegendarymarc/php-ogp``
  
Include the library and call Parser's ::parse() function.   
  
Example:  
  
```php  
 require_once('vendor/autoload.php');  
 $content = file_get_contents("https://www.youtube.com/watch?v=EIGGsZZWzZA");    
 print_r(\ogp\Parser::parse($content));  
```  
  
Author  
------  
  * Marc <marc@retz.io>
* Orginal Marcus Povey <marcus@marcus-povey.co.uk>  
 
