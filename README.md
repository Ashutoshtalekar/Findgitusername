# Find-Git-Acc
* Problem Statement: A web portal to find the profiles of Github accounts and information about their repositories.Now a days there are many computer students who use GitHub as one of platform for their studies, but sometimes they  have barrier while finding trustworthy and best information containing repositories. so this web portal will help students seeking for good repositories just by entering the name of the repository or the account. After entering the account name on that web we will get to see the username of repository holder, bio, link for the repository, profile info.


* Project Description : The Core idea behind this project is to provide young coding enthusiasts a platform to find the profiles of a github user and information about their repositories and their projects so that it'll be more convenient for coders to get to know about helpful accounts and repos. Using this platform the user will be able to get to know about the repositories that are there on github, there will be some information regarding their education , their  whereabouts. 

* Technology Stack :
1. HTML & CSS,JavaScript
2. Microsoft Azure services
3. VisualStudio Code IDE


* Azure technology used :
5. Storage Accounts (Containers) :

*  An Azure storage account contains all of your Azure Storage data objects, including blobs, file shares, queues, tables, and disks. 

* The storage account provides a unique namespace for your Azure Storage data that's accessible from anywhere in the world over HTTP or HTTPS. 

* Data in your storage account is durable and highly available, secure, and massively scalable.


2. Storage accounts static website :

* You can serve static content (HTML, CSS, JavaScript, and image files) directly from a storage container named $web.

* Azure Storage static website hosting is a great option in cases where you don't require a web server to render content.

## DEPENDABOT :
A git dependabot is also used.
Dependabot alleviates that pain by updating your dependencies automatically, so you can spend less time updating dependencies and more time building.

* API's Used : 
Total 3 API' are used {fetchData.js}
1. To fetch the default data.
2. To get user input.
3. To fill the data.

* step by step process to deploy a website :- 

Step 1: Login to your azure portal and create a storage account first.


![Screenshot (11)](https://user-images.githubusercontent.com/98150219/175519158-0ee257dd-ad17-43bc-8b39-ab1a2a5151de.png)

Step 2: After Creating a storage account, on that same page select static Website in data management section in resources in the column on left side. After selecting the another page will appear which will be asking you to create a website. By clicking on the enable option on that page your website will be generated automatically and will be served from the container $web. Give the index document and error document name and save the changes made.

![Screenshot (9)](https://user-images.githubusercontent.com/98150219/175519097-8f33b1df-6934-4e35-a6a9-967553bd403b.png)


Step 3: Now go to the storage, open the containers and upload the website code files which are code using VisualStudio Code as an IDE and images that are required for .

![Screenshot (12)](https://user-images.githubusercontent.com/98150219/175519400-5c137684-5004-4512-9b64-cda42c3c1b8c.png)

Step 4 : Once done with all of this copy the link that was generated earlier and paste it in browser . 
                  
         
         --------------------------YOUR WEBSITE WILL BE READY TO WORK-------------------------------    

Project demo website URL : https://ashutoshstorageaccount.z10.web.core.windows.net/

Demo video link : https://youtu.be/__U_nN37u9c
 
After Images :

![Screenshot (14)](https://user-images.githubusercontent.com/98150219/175519016-13bfbb42-1dff-4b72-b118-f4543f42d1b3.png)

![Screenshot (13)](https://user-images.githubusercontent.com/98150219/175518981-760c38ca-9a59-4e1d-97b4-fbc3b601cf87.png)

