# oracedb_datafile_size
This script will provide all datafile size from database

````sql
[oracle@localhost ~]$ sh oracledb_datafile_size.sh

===================================================
This script Shows the DATAFILES Size on a database.
===================================================


TABLESPACE_NAME                FILE_NAME                                                                                   Size   Max_Size
------------------------------ ------------------------------------------------------------------------------------- ---------- ----------
SYSAUX                         /u01/Oracle_datafiles/ORCL21C/datafile/o1_mf_sysaux_ktcp4pxs_.dbf                            660 32767.9844
SYSTEM                         /u01/Oracle_datafiles/ORCL21C/datafile/o1_mf_system_ktcp3m4d_.dbf                           1340 32767.9844
TEMP                           /u01/Oracle_datafiles/ORCL21C/datafile/o1_mf_temp_ktcp5hf6_.tmp                              237 32767.9844
UNDOTBS1                       /u01/Oracle_datafiles/ORCL21C/datafile/o1_mf_undotbs1_ktcp56by_.dbf                          120 32767.9844
USERS                          /u01/Oracle_datafiles/ORCL21C/datafile/o1_mf_users_ktcp57gk_.dbf                               5 32767.9844

[oracle@localhost ~]$
````
