Advanced Java Collections Activity Version 1.0-SNAPSHOT 8/7/2018

PROGRAM 

=================================================================

This program is an activity which makes use of the following:

- Java

- Maven (Build-Tool)

- JUnit FrameWork 

- Mockito Mocking FrameWork

- Jacoco Plugin

=================================================================

HOW TO RUN THE PROGRAM 

=================================================================

1. Download Zip File Containing the program and extract files. 

2. Or you could also clone the git repository if you have git installed in your computer. To do this, just copy the Git Repository Web URL then go to your terminal and execute git clone URL. 

3. Open the Terminal or Command Prompt in your PC. 

4. Through the appropriate commands (cd in linux), go to the folder of maven with testing which contains the pom.xml.

5. Once there, run 'mvn clean package' into the command line. This command and phase would run every phase until package which includes test. 

6. If you want to just test and not package the program, you can simply type 'mvn clean test'. 

NOTE: You could run the program without the clean phase but this is not advisable. This is due to the fact that compiled classes will remain on the target file without cleaning. There are also certain plugins that may require cleaning before it works properly.

7. Once the program is packaged, you can execute the jar file through the following ways:

 - Execute java -jar app/target/com.apm.app-MainApp-1.0-SNAPSHOT.jar

 - Or you could also go to the file directory of app/target first through 'cd app/target/' before running the command 'java -jar com.apm.app-MainApp-1.0-SNAPSHOT. 
=================================================================

Checking the Jacoco Plugin

=================================================================

**** The Jacoco Plugin in Maven can show you the code coverage of the tests. To do this, just run the mvn test or mvn package and the Jacoco Plugin would also be executed. *******

1. To check the results of code coverage from Jacoco, go to the module you wish to check (i.e. App, Service).

2. Go to target/site/jacoco

3. Open Index.html using your browser.

NOTE: If options does not give you an "OPEN WITH" or "Open with Browser" option, you could simply copy the full path of the index.html and paste the full path on your browser. 

4. The information you'll see indicates the code coverage of the tests on the current module.

=================================================================

All Rights Reserved 2018 - Adrian Paolo M. Molina


