# File REST API Example for Mule 4.x

This project is an example of a File REST API that shows how to POST a file. It includes the RAML spec and the Mule application. The Mule app, takes the file as multipart/form-data and and saves it to a folder in the app. This can be re-purposed to save the file to S3 or an FTP server.

### HTTP POST Request

When making the POST rquest, set the body to **form-data** and make sure the **key** for the file is named **fileName**

<img src="https://raw.githubusercontent.com/djuang1/file-rest-api-mule4/master/docs/fileName.png" width="500"/>

