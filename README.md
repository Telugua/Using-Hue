# Using-Hue
## 44517-02
## Group number: 02
## Topic: Using Hue

## Link to Repository: 
- [Github](https://github.com/Telugua/Using-Hue)

## Team Members:
1. Abhishek Telugu
1. Nandini Yadav Janga
1. Chaitra Vemula

![teamSlide](TeamSlide.PNG)

## Workshop Guide:
- Open browser in cloudera virtual machine and select Hue at the top of navigation bar

![openHue](/images/openHue.PNG)

- After clicking on Hue on the navigation bar you will be asked to login to Hue use username and password as cloudera

![LoginHue](/images/LoginHue.PNG)

- on the left side of screen select Hive from sources

![sources](/images/sources.PNG)

- Go to file browser by selecting menu icon on the left side of screen in previous image. By clicking on the menu icon we will get   different options in which one option would be files you will go to file browser by clicking on files. Go to user directory and select Hive.

![files](/images/Files.PNG)

- then select warehouse and upload the file you want to query on in this folder.

![warehouse](/images/Warehouse.PNG)

- Upload a file in warehouse folder by using uplooad option on the right of the screen.

![Upload](/images/Upload.PNG)

![AfterUpload](/images/AfterUpload.PNG)

- Now add a table to the database default by selecting + icon beside the option tables as seen in the previous image. after clicking on + icon the screen would look like this, mention the path in which you had uploaded a file in hive/warehouse folder to create the table in the database and then click on next.

![UploadTable](/images/uploadtabletodb.PNG)

- The next step would look like the image shown below the fields in the table are autofilled as the column names in the csv file you uploaded into hive folder earlier. Note that there should not be any spaces in the field names and then click on submit.

![step2UploadTable](/images/step2touploadfiletodb.PNG)

![fields](/images/Fields.PNG)

- After clicking on submit the screen would look like the image below.

![final](/images/finaldb.PNG)

- Now go to Hive editor to query on the table by clicking on Query option on the top of screen.

![Query](/images/Query.PNG)

- Now write a query to get the data as per your requirement from the file you uploaded.

![WriteQuery](/images/Writequery.PNG)

- Run your query 

![RunQuery](/images/RunQuery.PNG)

- After 1 minute your results will be displayed in a window down to the query section.

![Results](/images/Results.PNG)

- In this way we can use Hue to write and execute queries in Hive.

## References

- https://docs.cloudera.com/documentation/enterprise/5-9-x/topics/hue.html
















