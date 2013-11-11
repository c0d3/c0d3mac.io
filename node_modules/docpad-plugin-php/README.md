# PHP Plugin for DocPad
Adds support to [DocPad](https://docpad.org) for writing your templates using [PHP](http://www.php.net/manual/en/language.basic-syntax.phpmode.php)

Convention:  `.anything.php|phtml`

**Note:** this plugin provides PHP the template data, but you will not be able to call the template helpers as there is no easy way for php to communicate with javascript (which is what DocPad is built with), as such, you will probably want to use the [eco plugin](http://docpad.org/plugin/eco) instead.


## Install

```
npm install --save docpad-plugin-php
```


## History
You can discover the history inside the `History.md` file


## License
Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/)
<br/>Copyright &copy; 2012 [Bevry Pty Ltd](http://bevry.me)
<br/>Copyright &copy; 2011 [Benjamin Lupton](http://balupton.com)
