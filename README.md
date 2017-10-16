# Website-Notes

## realtor.jongriffith.com

- Disabled Cron in Wordpress and enabled it at the cPanel level.  define('DISABLE_WP_CRON', true);

## scottresidentialgroup.com

- Cron is disabled in Wordpress.  
- define('DISABLE_WP_CRON', true);
- Cron is enabled at the cPanel level `0	*	*	*	*	wget http://scottresidentialgroup.com/wp-cron.php`
- Additional Cron job on cPanel `56	1	*	*	*	/usr/local/bin/perl /usr/local/cpanel/3rdparty/quickinstall/scripts/checkupdates.pl`
