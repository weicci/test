# test
create db;
composer update;
php bin/magento setup:upgrade;
php bin/magento setup:di:compile;

sudo chgrp -hR www-data /dir;sudo chown -R www-data: /var/www/;sudo chmod -R 777 /dir;

setup begin
