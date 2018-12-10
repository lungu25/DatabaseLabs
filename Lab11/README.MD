# Laboratory work 10

### Task for Laboratory work nr 10:

### Task nr 1:
Sa se creeze un dosar Backup_labll. Sa se execute un backup complet al bazei de date universitatea in acest dosar. Fisierul copiei de rezerva sa se numeasca exercitiull.bak. Sa se scrie instructiunea SQL respectiva. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab11/Lab11Screens/Task1.PNG)

### Task nr 2:
Sa se scrie instructiunea unui backup diferentiat al bazei de date universitatea. Fisierul copiei de rezerva sa se numeasca exercitiul2.bak. 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab11/Lab11Screens/Task2.PNG)

### Task nr 3:
Sa se scrie instructiunea unui backup al jurnalului de tranzactii al bazei de date universitatea. Fisierul copiei de rezerva sa se numeasca exercitiul3.bak 

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab11/Lab11Screens/Task3.PNG)

### Task nr 4:
Sa se execute restaurarea consecutiva a tuturor copiilor de rezerva create. Recuperarea trebuie sa fie realizata intr-o baza de date noua universitatea_labll. Fisierele bazei de date noise afla in dosarul BD_labll. Sa se scrie instructiunile SQL respective

#### Sollution:
![alttext](https://github.com/lungu25/DatabaseLabs/blob/master/Lab11/Lab11Screens/Task4.PNG)

### Conclusion:
During this laboratory I understand that,types of backups are:
copy-only backup
A special-use backup that is independent of the regular sequence of SQL Server backups.

data backup
A backup of data in a complete database (a database backup), a partial database (a partial backup), or a set of data files or filegroups (a file backup).

database backup
A backup of a database. Full database backups represent the whole database at the time the backup finished. Differential database backups contain only changes made to the database since its most recent full database backup.

differential backup
A data backup that is based on the latest full backup of a complete or partial database or a set of data files or filegroups (the differential base) and that contains only the data extents that have changed since the differential base.

A differential partial backup records only the data extents that have changed in the filegroups since the previous partial backup, known as the base for the differential.

full backup
A data backup that contains all the data in a specific database or set of filegroups or files, and also enough log to allow for recovering that data.

log backup
A backup of transaction logs that includes all log records that were not backed up in a previous log backup. (full recovery model)

file backup
A backup of one or more database files or filegroups.

partial backup
Contains data from only some of the filegroups in a database, including the data in the primary filegroup, every read/write filegroup, and any optionally-specified read-only files.
