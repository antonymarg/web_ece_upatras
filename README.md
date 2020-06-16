# bus-ece-upatras
Semester project on Web Technologies ece upatras.  
  
## Οδηγείες εγκατάστασης  
1)	Εγκατάσταση της MongoDB: https://docs.mongodb.com/manual/administration/install-community/
2)	Εγκατάσταση του NodeJS (LTS version) από https://nodejs.org/en/download/  
3)  Κατεβάστε το git από εδώ: https://git-scm.com/downloads
4)	Ανοίξτε το bash και  
a.	`git clone https://github.com/mageirakos/web_ece_upatras.git`     
b.	`cd web_ece_upatras`      
c.	`npm install`    


### Setup the database:   
1)	Σε ένα terminal γράψτε  ` mongod` για να ανοίξει ένα mongo server
      Σε περίπτωση που δεν αναγνωρίζει το ' mongod ' ακολουθήστε τις εξής οδηγίες: https://dangphongvanthanh.wordpress.com/2017/06/12/add-mongos-bin-folder-to-the-path-environment-variable/
2)	Σε ένα άλλο terminal μεταφερθείτε στο directory της εγκατάστασης του repository και  
    -	`mongostore --db bus_ece  /dump/bus_ece`    
  

## Deployment   
1)	Σιγουρευτείτε ότι η βάση έχει εγκατασταθεί σωστά ελέγχοντας μέσω του MongoDB Compass τα περιεχόμενα.  
2)	Σιγουρευτείτε ότι ο server της βάσης είναι ανοικτός έχοντας γράφει `mongod` σε κάποιο terminal   
3)	Στο directory του repo γράψτε `node app.js`  σε ένα terminal    
4)	Μεταφερθείτε στο localhost:3000  

