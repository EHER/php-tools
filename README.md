#php-tools
Install php console tools with composer

Tools included:
- phpcs
- phpwatch

##How to install

```bash
git clone https://github.com/EHER/php-tools.git ~/.php-tools
cd ~/.php-tools
curl -sS https://getcomposer.org/installer | php
php composer install
```

##Configure Path

Add this to .bash_profile:

```bash
export PATH="$PATH":~/bin
```

If you don't have a .bash_profile, just create it.

