## Laravel Bukkit Console
Laravel package providing remote access to a Bukkit server console using JS/PHP/Laravel and the SwiftAPI Bukkit plugin

##### Preview screenshots
screenshots

### Version 0.1.0 Beta
[View changelog and todo](https://github.com/RobinRadic/laravel-bukkit-console/blob/master/changelog.md)

##### Requirements
- PHP > 5.3 
- Laravel > 4.0
- [Laravel Bukkit SwiftApi](https://github.com/RobinRadic/laravel-bukkit-swiftapi)


##### Installation
Require with composer:
```Batchfile
composer require radic/bukkit-console
php artisan config:publish radic/bukkit-console
php artisan asset:publish radic/bukkit-console
php artisan view:publish radic/bukkit-console
```

##### Configuration

##### Further reading
- [Laravel Bukkit SwiftApi](https://github.com/RobinRadic/laravel-bukkit-swiftapi). The SwiftAPI laravel wrapper
- [Bukkit SwiftAPI](http://dev.bukkit.org/bukkit-plugins/swiftapi). The SwiftAPI Website.
- [SwiftAPI Thrift Documentation](http://willwarren.com/docs/swiftapi/latest/). The docs for SwiftAPI generated Thrift code.
- [Bukkit SwiftAPI Reposiotry](https://bitbucket.org/phybros/swiftapi). Repository for the SwiftApi Bukkit Java plugin.

### Credits
- [Robin Radic](https://github.com/RobinRadic) created [Laravel Bukkit SwiftApi](https://github.com/RobinRadic/laravel-bukkit-console)
- [Phybros](http://dev.bukkit.org/profiles/phybros) created [Bukkit SwiftAPI](http://dev.bukkit.org/bukkit-plugins/swiftapi)

### License
[Do What the Fuck You Want to Public License](http://www.wtfpl.net/)