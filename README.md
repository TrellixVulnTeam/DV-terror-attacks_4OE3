# DV-terror-attacks
Data visulization of terror attacks from 1970 to 2016
requirements :
  - Install mondodb
  - Download terroristAttackData.zip and extract it to a certain (say workspace) 
  - Import data using the following command in the directory in which  the data is extracted
       mongoimport -d terrorDatadb -c projects --type csv --file hitPlacesDataset.csv --headerline
  - run app.py