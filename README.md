# PHP Eyecare

PHP >= 5.4
Based on [JoliNotif, the missing PHP notifier](https://github.com/jolicode/JoliNotif)

PHP Eyecare is tiny tool that helps you protect your eyes by [20 20 20 rule](http://en.wikipedia.org/wiki/Computer_vision_syndrome#Therapy).

## Installation

Use [Composer](http://getcomposer.org/) to install **PHP EyeCare** globally:

```shell
composer global require "khanhicetea/php-eyecare"
cd ~
sudo ln -s `pwd`/.composer/vendor/php-eyecare/eyecare /usr/local/bin/eyecare
sudo chmod +x /usr/local/bin/eyecare
```

## Usage

Run `eyecare` file terminal

```shell
eyecare
```

or add it to startup applications

- Ubuntu : System -> Preferences -> Startup Applications

## Credits

* [All contributors](https://github.com/khanhicetea/php-eyecare/graphs/contributors)
* This project was originally inspired by [ndksolution/eyecare](https://github.com/ndksolution/eyecare)

## License

PHP Eyecare is licensed under the MIT License - see the [LICENSE](LICENSE) file
for details.