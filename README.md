# Docker WordpressCity

hub.docker.com
wordpress

docker pull wordpress

`Try in PWD`
https://labs.play-with-docker.com/
https://labs.play-with-docker.com/sessions/cgl17j2e69v000a5fnj0/instances/cgl17j2e_cgl17jae69v000a5fnjg/editor


di terminal docker container:
```
curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
```
```
php wp-cli.phar --info
```
```
chmod +x wp-cli.phar
```
```
mv wp-cli.phar /usr/local/bin/wp
```
```
wp cli --info
```
$ wp --info
OS:     Linux 5.10.60.1-microsoft-standard-WSL2 #1 SMP Wed Aug 25 23:20:18 UTC 2021 x86_64
Shell:  /usr/bin/zsh
PHP binary:     /usr/bin/php8.1
PHP version:    8.1.0
php.ini used:   /etc/php/8.1/cli/php.ini
MySQL binary:   /usr/bin/mysql
MySQL version:  mysql  Ver 8.0.27-0ubuntu0.20.04.1 for Linux on x86_64 ((Ubuntu))
SQL modes:
WP-CLI root dir:        /home/wp-cli/
WP-CLI vendor dir:      /home/wp-cli/vendor
WP_CLI phar path:
WP-CLI packages dir:    /home/wp-cli/.wp-cli/packages/
WP-CLI global config:
WP-CLI project config:  /home/wp-cli/wp-cli.yml
WP-CLI version: 2.7.1
