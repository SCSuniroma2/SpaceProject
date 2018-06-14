# SpaceProject
Progetto Basi di Dati 2018
1. Per poter utilizzare l'applicazione occorre: 
	i.   DBMS PostresSQL
	ii.  IDE Eclipse
	iii. File "DbProject.zip" scaricabile da questo repository
	iv.  File "dump_completo.sql" scaricabile da questo link:  
		https://drive.google.com/open?id=1NR_LDYoAYL3kECtilMOkYaZC7nlFyEQg

2. Prima di avviare l'applicazione è necessario importare il dump del database.
   E' possibile farlo da terminale digitando:
		psql -U nome_utente -d nome_database < dump_completo.sql

3. Per avviare l'applicazione procedere come segue:
	i.   Aprire l'IDE Eclipse
	ii.  Cliccare su 
	       File
	       >Open Projects from File System
	       >Archive
	       >Selezionare il file "DbProject.zip"
	       >Mantenere selezionata solo la cartella riferita a 'Eclipse project'
	       >Finish
	iii. Modificare il file src/controller/DBHandler.java con i vostri parametri di accesso al database
	iv.  Avviare l'interfaccia eseguendo il file src/main/main.java


4. E' possibile effettuare il login come amministratore inserendo:
		Username: spaceproject
		Password: database
   Come utente normale inserendo:
		Username: rossimario
		Password: rossimario


Si può inoltre partire da un database vuoto:
	i.   Scaricare file "schema.sql" presente in questo repository
	ii.  Scaricare file "init_data.sql" presente in questo repository
	iii. Eseguire l'import di i) e successivamente di ii) come descritto al punto 2)
	iv.  Avviare l'applicazione come in 3) e utilizzare le credenziali come in 4)



