PROBLEM SOLUTION

brew uninstall mariadb --force [uninstall MariaDB]
rm -rf /usr/local/var/mysql/ [remove mysql log folder]
rm -rf /usr/local/etc/my.cnf [remove mysql global option files]
rm -rf /usr/local/etc/my.cnf.d [remove mysql global option files]
rm -rf /usr/local/etc/my.cnf.default [remove mysql global option files]
brew install mariadb [install MariaDB]
brew services start mariadb
sudo /usr/local/bin/mysql_secure_installation
