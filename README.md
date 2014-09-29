#php-tools
Php console tools installed with composer

Tools included:
- [composer] - Dependency Manager for PHP
- [pdepend] - This tool shows you the quality of your design in the terms of extensibility, reusability and maintainability
- [php-cs-fixer] - Analyzes some PHP source code and tries to fix coding standards issues (PSR-1 and PSR-2 compatible)
- [phpcs] - PHP_CodeSniffer tokenises PHP, JavaScript and CSS files and detects violations of a defined set of coding standards
- [phpmd] - PHPMD is a spin-off project of PHP Depend and aims to be a PHP equivalent of the well known Java tool PMD
- [phpspec] - SpecBDD Framework for PHP
- [phpunit] - The PHP Unit Testing framework
- [phpwatch] - Command line client that allow you to run arbitrary shell commands whenever changes occur in a list of specified files
- [twig-lint] - Twig-lint is a lint tool for your twig files

##Install in 3 steps

1. Clone the repository
```bash
git clone https://github.com/EHER/php-tools.git ~/.php-tools
```

2. Get [composer]
```bash
cd ~/.php-tools
curl -sS https://getcomposer.org/installer | php
mkdir -p ~/bin
mv composer.phar ~/bin/composer
```

3. Install
```bash
~/bin/composer install
```

##Configure Path

Add this to .bash_profile
```bash
export PATH="$PATH":~/bin
```
If you don't have a .bash_profile, just create it.

[composer]: http://getcomposer.org/
[pdepend]: https://github.com/pdepend/pdepend
[php-cs-fixer]: https://github.com/fabpot/php-cs-fixer
[phpcs]: https://github.com/squizlabs/PHP_CodeSniffer
[phpmd]: https://github.com/phpmd/phpmd
[phpspec]: https://github.com/phpspec/phpspec
[phpunit]: https://github.com/sebastianbergmann/phpunit
[phpwatch]: https://github.com/EHER/phpwatch
[twig-lint]: https://github.com/asm89/twig-lint

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/EHER/php-tools/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
