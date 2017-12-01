# CM
## ls /etc/yum.repos.d
```
total 28
-rw-r--r--. 1 root root 1664 Aug 30 10:53 CentOS-Base.repo
-rw-r--r--. 1 root root 1309 Aug 30 10:53 CentOS-CR.repo
-rw-r--r--. 1 root root  649 Aug 30 10:53 CentOS-Debuginfo.repo
-rw-r--r--. 1 root root  314 Aug 30 10:53 CentOS-fasttrack.repo
-rw-r--r--. 1 root root  630 Aug 30 10:53 CentOS-Media.repo
-rw-r--r--. 1 root root 1331 Aug 30 10:53 CentOS-Sources.repo
-rw-r--r--. 1 root root 3830 Aug 30 10:53 CentOS-Vault.repo
```
##  /usr/share/cmf/schema/scm_prepare_database.sh -h ip-10-1-2-207.ec2.internal mysql scm user1 cloudera2017!
```
JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera
Verifying that we can write to /etc/cloudera-scm-server
Creating SCM configuration file in /etc/cloudera-scm-server
Executing:  /usr/java/jdk1.7.0_67-cloudera/bin/java -cp /usr/share/java/mysql-connector-java.jar:/usr/share/java/oracle-connector-java.jar:/usr/share/cmf/sche          ma/../lib/* com.cloudera.enterprise.dbutil.DbCommandExecutor /etc/cloudera-scm-server/db.properties com.cloudera.cmf.db.
[                          main] DbCommandExecutor              INFO  Successfully connected to database.
All done, your SCM database is configured correctly!
```
