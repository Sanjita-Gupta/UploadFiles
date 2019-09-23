# MultipleFilesUpload
Create a directory at appropriate location/drive like '/DemoFileUpload'.
cd DemoFileUpload
git clone https://github.com/saura-bh/MultipleFilesUpload.git
All files will be cloned under directory /MultipleFilesUpload
cd MultipleFilesUpload
run MVN commands to initialize and download dependencies into project.
mvn install
mvn clean package
JUnit tests already included and checked during compile time also.
After running MVN commands, project will be initialized and build the executable JAR file to run.
Run the below command to RUN the jar file.
java -jar target/singtel-uploading-files-0.1.0.jar

That runs the server-side piece that receives file uploads and should be up and running within a few seconds.
Open a browser and visit http://localhost:8080/ to see the upload form and upload multiple files.

Note: I have added VirusTotal Public API v2.0 Client implementation in Java to scan files but we have to buy licenese and key. 
I have written code to scan each file but commented out that code part.
