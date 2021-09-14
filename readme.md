### Wordpress Docker – upload_max_filesize ändern
1. php.ini erstellen vim /var/www/html/php.ini

> upload_max_filesize = 256M \
post_max_size = 256M \
memory_limit = 256M 


2. Speichern und Container neu starten. 
