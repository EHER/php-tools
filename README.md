#php-tools
Php console tools installed with composer

Tools included:
- [php-cs-fixer][php-cs-fixer] - Analyzes some PHP source code and tries to fix coding standards issues (PSR-1 and PSR-2 compatible)
- [phpcs][phpcs] - PHP_CodeSniffer tokenises PHP, JavaScript and CSS files and detects violations of a defined set of coding standards
- [phpwatch][phpwatch] - Command line client that allow you to run arbitrary shell commands whenever changes occur in a list of specified files

##Install in 3 steps

1. Clone the repository
```bash
git clone https://github.com/EHER/php-tools.git ~/.php-tools
```

2. Get [composer]
```bash
cd ~/.php-tools
curl -sS https://getcomposer.org/installer | php
```

3. Install
```bash
php composer.phar install
```

##Configure Path

Add this to .bash_profile
```bash
export PATH="$PATH":~/bin
```
If you don't have a .bash_profile, just create it.

[php-cs-fixer]: https://github.com/fabpot/php-cs-fixer
[phpcs]: https://github.com/squizlabs/PHP_CodeSniffer
[phpwatch]: https://github.com/EHER/phpwatch
[composer]: http://getcomposer.org/
