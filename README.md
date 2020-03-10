orchestrator-unit-test: Unit Test for JBoss PAM Project
======================================================
Author: Nevin Zhu  
Level: Intermediate  
Technologies: JBoss PAM 7.x, JUnit
Summary: The `orchestrator-unit-test` is a maven project specifically for running JUnit test cases for Malware NextGen's orchestrator project 
Target Product: N/A  

What is it?
-----------

The `orchestrator-unit-test` demonstrates how to build and run JUnit test cases for BPMN workflow built in JBoss PAM 7.x

It contains the following:

1. JUnit test case that validates an instance of process is active.
2. JUnit test case that validates a particular node in the workflow is triggered. 



System requirements
-------------------

The application this project produces is designed to be run on maven 3.x

All you need to build this project is Java 8.0 (Java SDK 1.8) or later, Maven 3.0 or later.

 
Configure Maven
---------------

If you have not yet done so, you must [Configure Maven](p:/Nevin/Raytheon - PAM 7 AWS Installation - v1.0.docx) before running the project.


Build and run the Project
-------------------------

_NOTE: The following build command assumes you have configured your Maven user settings. If you have not, you must include Maven setting arguments on the command line. 

1. Open a command prompt and navigate to the root directory of this project.
2. Type this command to build and run the project:

        mvn test
        


Investigate the Console Output
------------------------------------

If the Maven command is successful, you will see output similar to this:

```text
Results :

Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.926 s
[INFO] Finished at: 2020-03-09T23:05:16-04:00
[INFO] ------------------------------------------------------------------------
```
   

