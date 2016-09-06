Trois services
-

la persistance des données est assurés pour :
* le site
* la base de données
* les logs avec log
* limitation des ressources à 120 MO pour php et nginx

* mariadb
	+ "/home/data/${PATH}/mysql:/var/lib/mysql"
* php:fpm
	+ "/home/data/${PATH}/public_html/:/var/www/html"
* nginx
	+ "/home/data/${PATH}/public_html/:/var/www/html"
