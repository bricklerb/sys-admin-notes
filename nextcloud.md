### Cron
Add the following to your cron tab `*/5 * * * * docker exec -u www-data nextcloud php /var/www/html/cron.php` to allow nextcloud cron to execute
