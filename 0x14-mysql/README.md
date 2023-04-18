# Resources
* <a href="https://www.digitalocean.com/community/tutorials/how-to-choose-a-redundancy-plan-to-ensure-high-availability#sql-replication">What is a primary-replica cluster</a>
* <a href="https://www.digitalocean.com/community/tutorials/how-to-set-up-replication-in-mysql">MySQL primary replica setup<a/>
* <a href="https://www.databasejournal.com/ms-sql/developing-a-sql-server-backup-strategy/">Build a robust database backup strategy</a>

Mysql
This project involved learning how to configure database servers in a primary-replica model. I configured the two servers provided to me by Holberton School in a MySQL primary-replica setup with a dummy database, and wrote a Bash script to automate generation of database backups.

Tasks 📃
4-mysql_configuration_primary: The MySQL my.conf configuration file used to set up my first server as a primary database server on the database tyrell_corp.

4-mysql_configuration_replica: The MySQL my.conf configuration file used to set up my second server as the replica database server on the database tyrell_corp.

5-mysql_backup: Bash script that generates a compressed tar.gz archive from a MySQL dump.

Usage: ./5-mysql_backup <MySQL root password>
Generates a dump containing all MySQL databases on the root server.
Names the resulting tar archive in the format day-month-year.tar.gz.
