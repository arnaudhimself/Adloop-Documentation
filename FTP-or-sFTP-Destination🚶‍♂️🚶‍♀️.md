Adloop sends and updates the exports in a folder available on a FTP server (port 21) or sFTP (port 22). 

The process and the fields to fill in are the same for FTP and sFTP. The only difference is that sFTP uses an encryption key to secure the data.  

To allow Adloop to write in your FTP, you must connect it to Adloop with:  


1. The server FTP address


1. Login and password


1. A folder name, if needed




## 1 - Allow Adloop to access your FTP
The connection process is just filling in the form boxes. 

 **Login and password** (sent by a system admin)

![](images/storage/image-20220301-162020.png)

 **Host** : address of your FTP server

noteIt must look like this: [ftp.company.com](http://ftp.company.com)

It must look like this: [ftp.company.com](http://ftp.company.com)

![](images/storage/image-20220301-162041.png) **Port** : fill in the desired FTP port

note21 is the FTP default port / 22 is the sFTP default port

You can use another port, sent by your system admin

21 is the FTP default port / 22 is the sFTP default port

You can use another port, sent by your system admin

![](images/storage/image-20210520-140428.png) **Destination Folder** : indicate the folder in which the files will be dropped.

![](images/storage/image-20220301-162111.png)
## 2 - Submitting and checking the connection
By clicking on Submit, your connection will be checked according to your parameters. 

In case the connection fails, you will have an alert: 

![](images/storage/image-20210520-140851.png)If the connection is OK, you just need to name this Destination and you are done! 

Your FTP or sFTP destination will now appear in your destinations list. 



*****

[[category.storage-team]] 
[[category.confluence]] 
