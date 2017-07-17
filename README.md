# php5-security

Secure configuration for PHP

## 1) Install the module

```
sudo wget https://raw.githubusercontent.com/isgroup-srl/php5-security/master/security.ini -O /etc/php5/mods-available/security.ini
```

## 2) Enable the module

```
sudo php5enmod security
```

## 3) Restart your services

```
sudo /etc/init.d/apache2 restart
```

```
sudo /etc/init.d/php5-fpm restart
```
