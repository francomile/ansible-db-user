# Ansible Database Proxy User Creation Role for Debian(7,8) Servers using MySQL   

## This role will create a system proxy user and a MySQL user for safe database connections.  

1. Create a proxy user in system named dbmaster for accessing through SSH
2. Create `.ssh` directory and the authorized_keys file from a template for `dbmaster` user
3. Create the `.bashrc` file from a template for `dbmaster` user
4. Create a  `mysql_user` user in the MySQL database and grant permissions
