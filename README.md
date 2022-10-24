### CHECK requirements_installer.sh and simple/composer_install_requirements.sh

# IN simple/vendor/.env you can set your SQL, Mysql, MariaDB or Postgresql user and passwrod as well as DB name. Update mysql,mariadb,... version. (SEARCH FOR DATABASE_URL)
# 127.0.0.1 may have to be changed to localhost depending on device config.

# To check all available command use:
php bin/console #in simple folder

# To create DB
php bin/console doctrine:database:create

# Create Entity representation (table)
php bin/console make:entity