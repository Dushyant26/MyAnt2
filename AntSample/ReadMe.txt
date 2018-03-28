Installation:
=============
1. Unzip the contents of the AntSampleProject.zip file into a directory of your choice

The project structure and contents should be as follows:
NOTE:  <...> indicate directory names.

<AntSample>
 +---ReadMe.txt                     <- Located in AntSample directory
 +---<proj>                             <- Project root directory
 +---+---build.xml                   <- Ant build file
 +---+---inventory.xml            <- Data file
 +---+---SaxParse.bat             <- Executes Java application
 +---+---<src>                         <- Java source directory
 +---+---+---Computer.java
 +---+---+---JavaSAXParse.java
 +---+---+---MyHandler.java

To build the project:
1.	Open a Command Prompt
2.	Navigate to the root directory ...\AntSample\proj
3.	Issue the command:  ...ant

To run the application:
1.	Open a Command Prompt
2.	Navigate to the root directory ...\AntSample\proj
3.	Issue the command:  SAXparse.bat





