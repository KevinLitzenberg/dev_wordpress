Compose File to build Wordpress with phpmyadmin to manage mysql.

Passwords have been moved to secrets and files have been ignored in .gitignore

Site data is loaded into mysql database utilizing a bitnami_wordpress.sql file.  This file is also added to the .gitigore file.

If building from this compose-file you will need to add your own password files and your own sql file from an sql.dump.
