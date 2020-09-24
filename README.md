<div align="center">

## Backup and restore MySQL DBs within Visual Basic


</div>

### Description

The purpouse of this module is to backup and restore mysql databases within a Visual Basic program.

Please, don't vote for this one... It is a remake of http://www.planetsourcecode.com/vb/scripts/ShowCode.asp?txtCodeId=57138&lngWId=1 which inspires me.

It has some improvement on his code: Basically, it take the table creation statement directly from the MySQL engine (so now it publish constrains and indexes correctly) and perfom only on insertion statement per table no matter the number of rows in the table.

Also, it prevent MySQL from generating errors because of the constraing and block the tables before the insertion process.

Also, it could allows the programmers to give feedback to the user about the process and, last but not least, it is IMHO a bit cleaner.
 
### More Info
 
Just the filename of the backup file and the connection (ADODB.Connection)

The connection should be a valid and active one.


<span>             |<span>
---                |---
**Submitted On**   |2005-03-25 13:56:04
**By**             |[Williams Castillo](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/williams-castillo.md)
**Level**          |Beginner
**User Rating**    |4.8 (29 globes from 6 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Databases/ Data Access/ DAO/ ADO](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/databases-data-access-dao-ado__1-6.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[Backup\_and1868073252005\.zip](https://github.com/Planet-Source-Code/williams-castillo-backup-and-restore-mysql-dbs-within-visual-basic__1-59638/archive/master.zip)








