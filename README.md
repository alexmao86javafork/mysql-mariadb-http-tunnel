# mysql-mariadb-http-tunnel
This allows you to make connections to a MySQL or MariaDB database over http.
You can use this script to connect to MySQL or MariaDB databases on a remote server which is behind a firewall or does not allow direct connections.

Author: Andre Dixon
Website: http://www.dredix.net

Note:
1. It is better to use this script over a secure (https) connection.
2. Connecting over SSH should always be explored an a option first.
3. The .htaccess file is included to prevent your directory from listing files within.
4. You can rename the index.php to add an extra level of security.

The orginal code for this script I got form the URL below. I then added the Basic Auth and IP address check.
https://gist.github.com/peterjaap/5151633
