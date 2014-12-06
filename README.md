#php-tools
Php console tools installed with composer

Tools included:
- [composer] - Dependency Manager for PHP
- [pdepend] - This tool shows you the quality of your design in the terms of extensibility, reusability and maintainability
- [php-cs-fixer] - Analyzes some PHP source code and tries to fix coding standards issues (PSR-1 and PSR-2 compatible)
- [phpcs] - PHP_CodeSniffer tokenises PHP, JavaScript and CSS files and detects violations of a defined set of coding standards
- [phpctags] - An enhanced ctags compatible index generator written in pure PHP
- [phpmd] - PHPMD is a spin-off project of PHP Depend and aims to be a PHP equivalent of the well known Java tool PMD
- [phpspec] - SpecBDD Framework for PHP
- [phpunit] - The PHP Unit Testing framework
- [phpwatch] - Command line client that allow you to run arbitrary shell commands whenever changes occur in a list of specified files
- [twig-lint] - Twig-lint is a lint tool for your twig files

##Install in 2 steps

1. Install and configure [composer]
  ```bash
  mkdir -p ~/bin
  php -r "readfile('https://getcomposer.org/installer');" | php -- --install-dir=bin --filename=composer -f
  ~/bin/composer global config bin-dir ~/bin
  ```
2. Add php-tools to global composer
  ```bash
  ~/bin/composer global require eher/php-tools
  ```

##Configure Path

Add this to .bash_profile
```bash
export PATH=~/bin:"$PATH"
```
If you don't have a .bash_profile, just create it.

[composer]: http://getcomposer.org/
[pdepend]: https://github.com/pdepend/pdepend
[php-cs-fixer]: https://github.com/fabpot/php-cs-fixer
[phpcs]: https://github.com/squizlabs/PHP_CodeSniffer
[phpctags]: https://github.com/vim-php/phpctags
[phpmd]: https://github.com/phpmd/phpmd
[phpspec]: https://github.com/phpspec/phpspec
[phpunit]: https://github.com/sebastianbergmann/phpunit
[phpwatch]: https://github.com/EHER/phpwatch
[twig-lint]: https://github.com/asm89/twig-lint

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/EHER/php-tools/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
