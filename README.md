# MultipleFilesUpload

1. Create a directory at appropriate location/drive like '/DemoFileUpload'.

2. cd DemoFileUpload

3. git clone

4. All files will be cloned under directory /MultipleFilesUpload

5. cd MultipleFilesUpload

6. run MVN commands to initialize and download dependencies into project.

7. mvn install

8. mvn clean package

9. JUnit tests already included and checked during compile time also.

10. After running MVN commands, project will be initialized and build the executable JAR file to run.

11. Run the below command to RUN the jar file.
		
		java -jar target/singtel-uploading-files-0.1.0.jar

12. That runs the server-side piece that receives file uploads and should be up and running within a few seconds. Open a browser and visit http://localhost:8080/ to see the upload form and upload multiple files.

Note: I have added VirusTotal Public API v2.0 Client implementation in Java to scan files but we have to buy licenese and key. 
I have written code to scan each file but commented out that code part.
