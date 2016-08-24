Trois services
-

la persistance des données est assurés pour : 
* le site 
* la base de données
* les logs

* mariadb
	+ "/home/data/${PATH}/mysql:/var/lib/mysql"
* php:fpm 
	+ "/home/data/${PATH}/public_html/:/var/www/html"
	+ "/home/data/${PATH}/log/php/:/usr/local/var/log"
* nginx
	+ "/home/data/${PATH}/public_html/:/var/www/html"
	+ "/home/data/${PATH}/log/nginx/:/var/log/nginx"