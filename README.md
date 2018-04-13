Compose File to build Wordpress with phpmyadmin to manage mysql.

Passwords have been moved to secrets and files have been ignored in .gitignore

Site data is loaded into mysql database utilizing a bitnami_wordpress.sql file.  This file is also added to the .gitigore file.

If building from this compose-file you will need to add your own password files and your own sql file from an sql.dump.

dev_wordpress-0.0.1: Changelog
-Pulls from kevinlitz custom WP image based on wordpress:4.9.5
-wordpress service ports are now set to 443/80 as the documentaion for WP Multi-site requires.
-Certifcates are not valid yet, as we are still in dev.
-Likely will be using AWS generated certs instead of Certbot, which will be decided once the containers are built in AWS.

