# wp-create-network
Convert a single Wordpress installation into a multisite.

# TODO
 - Edit virtual host file to allow wildcards
  - find line and add ServerAlias
  - File: /etc/apache2/sites-available/${SITENAME}.wpdev0.koumbit.net.conf 
  - After: ServerName ${SITENAME}.wpdev0.koumbit.net
  - Add: ServerAlias *.${SITENAME}.wpdev0.koumbit.net
 - wp core multisite-convert
