# mariadb-macos-clean-remove

PROBLEM SOLUTION

1. brew uninstall mariadb [uninstall MariaDB]
2. rm -rf /usr/local/var/mysql/ [remove mysql log folder]
3. rm -rf /usr/local/etc/my.cnf [remove mysql global option files]
4. rm -rf /usr/local/etc/my.cnf.d [remove mysql global option files]
5. rm -rf /usr/local/etc/my.cnf.default [remove mysql global option files]
6. brew install mariadb [install MariaDB]
7. brew services start mariadb
8. sudo /usr/local/bin/mysql_secure_installation
