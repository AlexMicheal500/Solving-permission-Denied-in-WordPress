# Solving-permission-Denied-in-WordPress-Plugins-Update
This is solved by changing var/www/html user and group using the following command:

sudo chown -R www-data:www-data /var/www

Then use a permission of 755 on both folder and file

e.g. chmod 755 plugins && chmod 755 cloudflare
