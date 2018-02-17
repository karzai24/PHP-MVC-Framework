# PHP-MVC-Framework
PHP-MVC-Framework
-Unzip file- 2 directories should show after unzip (app, public) these are the Framework files
-Setting up- (assuming LAMP stack Debian 8.0+)
Create new folder in var/www folder for the new apps directory
copy framework to the newly created folder
add new app name to /etc/hosts
add new app name to /etc/apache2/sites-available/{new.conf.file.for.new.app}
Change .htaccess files in framework to suit new application
Change config file app/config to reflect new database
Create new MySQL tables for new app (we need to find out all the information we need for different tables)
Inside pages controller change the title of the site
.htaccess file in public folder needs to change Rewrite base to view the new app name:
/newapp/public

-This should be everything you need to do to get this framework working for you
