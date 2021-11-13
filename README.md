# Description

a python based database to store data in json base64 format and also retrieve everything using a password, which is hashed using sha256 for security purposes.
## basic Functionalities;


- Get
- Post
- update
- clean 


# usage

#### GET functionality:

	Database --login [dbName] [password] => consoles all the data in the db.
	Database --login => will ask for dbName and paswword and outputs the db.
	Database --getHeaders [dbName] [password] => gets and consoles all the headers
	Database --getHeaders => gets and consoles all the headers (asks for name/password!)

	Database --getItems [dbName] [password] => get the items.

#### POST functionality:

	Database --register => to make new dataBase and password for it.
	Database --register  [dbName] [password]=> to Make db more quickly.
	Database --update [dbname] [password] [header] [data]

#### clearing a Database:
	Database --clear [dbname]  [password] 
	Database --clear

> Note: If there is anything that is not specified, there would be an input that asks for it.
this applies for all the flags.


#### To see the doc:
	
> 	Database --help or -h => to get some help.

my First database *[Database 1](https://github.com/Moody0101/PythonDatabase)*.
