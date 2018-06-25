# SpaceProject <img src="https://cdn1.iconfinder.com/data/icons/famfamfam_flag_icons/it.png">

Università degli studi di Roma Tor Vergata. Progetto di 'Basi di Dati' 2018.

## 1. Prerequisiti
Per poter utilizzare l'applicazione occorre:
```
i.   DBMS PostgresSQL
ii.  Eclipse IDE
iii. File "DbProject.zip" scaricabile da questo repository
iv.  File "dump_completo.sql" scaricabile dal seguente link:
```
[dump_completo.sql](https://drive.google.com/open?id=1NR_LDYoAYL3kECtilMOkYaZC7nlFyEQg)
	  
### 2. Installazione
Prima di avviare l'applicazione è necessario importare il dump del database. E' possibile farlo da terminale digitando:
```
psql -U nome_utente -d nome_database < dump_completo.sql
```

### 3. Avvio
Per avviare l'applicazione procedere come segue:
```
i.   Aprire Eclipse	
ii.  Cliccare su File->Open Projects from File System->Archive->Selezionare il file "DbProject.zip"->Mantenere selezionata solo la cartella riferita a 'Eclipse project'->Finish
iii. Modificare il file src/controller/DBHandler.java con i vostri parametri di accesso al database	
iv.  Avviare l'interfaccia eseguendo il file src/main/main.java
```

### 4. Credenziali di accesso
E' possibile effettuare il login come amministratore inserendo:
```
Username: spaceproject		
Password: database
```		
Come utente normale: 
```
Username: rossimario
Password: rossimario
```

##
Invece di effettuare il dump completo, si può inoltre utilizzare una demo del database, con informazioni di default:
```
i.   Scaricare file "schema.sql" presente in questo repository	
ii.  Scaricare file "init_data.sql" presente in questo repository	
iii. Eseguire l'import di i) e successivamente di ii) come descritto al punto 2)	
iv.  Avviare l'applicazione come in 3) e utilizzare le credenziali come in 4)
```	
	
## Autori
* **Cristiano Calicchia** (lufth)
* **Gabriele Sanelli** (thegabrielesa)
* **Flavio Scaccia** (flaxalf)


---


# SpaceProject <img src="https://cdn1.iconfinder.com/data/icons/ensign-11/512/273_Ensign_Flag_Nation_kingdom-512.png" height="16" width="16">

University of Rome, Tor Vergata. Project made for the exam of 'Basi di Dati' 2018.

## 1. Prerequisites
To use this application you need:
```
i.   DBMS PostgresSQL
ii.  Eclipse IDE
iii. "DbProject.zip" file, that can be downloaded from this repository
iv.  "dump_completo.sql" file, that can be downloaded from the following link
```
[dump_completo.sql](https://drive.google.com/open?id=1NR_LDYoAYL3kECtilMOkYaZC7nlFyEQg)
	  
### 2. Installing
Before you start the application, you may have to import the database's dump. You can do that by terminal, typing:
```
psql -U user_name -d database_name < dump_completo.sql
```

### 3. Getting started
To launch the application do as it follows:
```
i.   Open Eclipse
ii.  Click on File->Open Projects from File System->Archive->Select the file "DbProject.zip"->Keep checked only the folder refered to 'Eclipse project'->Finish
iii. Edit the file src/controller/DBHandler.java with yours access' parameters to the database	
iv.  Launch the interface running the src/main/main.java file
```

### 4. Login
You can login as an administrator typing:
```
Username: spaceproject		
Password: database
```		
As a normal user: 
```
Username: rossimario
Password: rossimario
```

##
Instead of doing the full dump, you have the possibility to use a database's demo, with default's informations:
```
i.   Download the "schema.sql" file, placed in this repository
ii.  Download the "init_data.sql" file, placed in this repository
iii. Perform the import of i) and then of ii) as written in point 2)	
iv.  Launch the application as in 3) and login as in 4)
```	
	
## Authors
* **Cristiano Calicchia** (lufth)
* **Gabriele Sanelli** (thegabrielesa)
* **Flavio Scaccia** (flaxalf)
