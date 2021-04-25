## Remote container
- mcr.microsoft.com/vscode/devcontainers/php
- mariadb

## API Tools
- https://api-tools.getlaminas.org/

## Config
- Execute os comandos abaixo para inixiar a aplicacao
```
sudo apt update -y
sudo apt install sqlite3 -y
composer create-project laminas-api-tools/api-tools-skeleton
cd api-tools-skeleton
php -S 0.0.0.0:8080 -t public public/index.php
```

## View
- http://localhost:8080/