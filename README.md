# IBM-Bluemix-Web-app-Cloudant-NoSQL-DB-and-hashing.
In IBM Bluemix cloud, create a Cloud Foundary App
Add Cloudant NoSQL DB service to the App
Update username, password,urlx environment variables from the App to assignment2.py
Deploy the application with CF CLI including the requirements.txt & cloudant-0.5.10.dist-info folder
cf push "The unique App name created in IBM bluemix"
Access app in browser with appname.mybluemix.net
upload,download,delete,list files
The file name is hashed for uniqueness & saved in NoSQl 
If the filename already exists & if the contents are same then upload is discarded
If the filename already exists & the file contents are different then the file is stored in a different version
