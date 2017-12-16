# Currencyhandler


**This simple script  grabs the current crypto currencies**  

usage : ./parserv2.8.sh 1.[logfile name] 2.[y/n] 3.[y/n] 4.[y/n] 5.[y/n]
		<db_path/db_name>[leave blank for default]  <y/n to Mark>  <y/n to query>  <y/n to read from terminal>  <y/n to create DB sorter file>

1. first parameter ; optional, logfile name can be specified 
2. second parameter ; optional, mark the current query 
3. third parameter ; optional, logfile can be searched 
4. fourth parameter ; optional, print to terminal
5. fifth parameter ; optional, create a database unique id logfile or use a previous one 


///// This section is for development /////

- [X]  script checks the internet connection and returns an echo []---
- [X]  script checks for api.list and if not present creates one []---
- [X]  add if there is a database file and make it default if there is none present or previous