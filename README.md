Download SQLLite in this version - 	sqlite-tools-win-arm64-3510100.zip
(5.24 MiB)
Extract the zip and move the sqlite.exe file into the /content folder of your EoS project.
Open your terminal in that folder and run: .open database/playerStats.db
Download grafana OSS for windows 
Open your browser and go to: http://localhost:3000
Login: * Username: admin Password: admin (Note: You will be prompted to change your password after the first login)
In the Grafana UI, add a new SQLite Datasource and point it to your .db file path.
Download the .json dashboard files from this GitHub repository.
Import: 1. In Grafana, go to Dashboards -> New -> Import. 2. Upload the .json file you just downloaded. 3. Select your SQLite data source when prompted.
