author: Huijuan (Ann) Huang
time: 02/19

What Is This?
-------------

This is Web Project "Comparison" for Philips Interview Task 
to find unique records of two uploaded files

Language:
Back end: Java (Servlet)
Front end: HTML, CSS, JSP(dynamic Java embedded HTML documents), Javascript, JQuery
Architecture: MVC
Libraries: JSTL, bootstrap
Server: Tomcat
(IDE: Eclipse)

How does this Application work
-----------------------
1. Under Eclipse IDE, run web application "philips' on t server 
2. choose Tomcat (right version) server
3. Application start
4. default web is http://localhost:8080/philips/ which is home entry page

How To Setup Configuration
--------------------------
1. Java
Download and install the latest Java SE JDK from Sun/Oracle
http://www.oracle.com/technetwork/java/javase/downloads/index.html
Set a JAVA_HOME environment variable to the directory where JDK is installed.

2. Tomcat
Download the latest Tomcat 7 binary release from the Apache Project.
http://tomcat.apache.org/download-70.cgi

Add the JAR files of the following libraries to the lib folder under the Tomcat directory:
jstl.jar and standard.jar from JSP Standard Tag Library (JSTL).


3. Eclipse
Download Eclipse IDE for Java EE Developers from Eclipse.org
http://www.eclipse.org/downloads/

4. Import project
Eclipse -> File -> Import -> General -> Exiting Projects in to workspace -> check path

5. Configure Build Path
Download JAR files of the following libraries to the philips/WebContent/WEB-INF/lid director:
commons-fileupload-1.3.1.jar
commons-io-1.3.2.jar

Configure build path
right click project -> Build Path -> Configure build path -> Libraries

5. Run project on the server
right click project -> Run As -> Run on Server -> ADD JARS -> 
add commons-fileupload-1.3.1.jar  and commons-io-1.3.2.jar two jars in the library

The first time it runs, it need to setup server, choose Tomcat (the right version) to start

Default web is http://localhost:8080/philips/ which is home entry page

6. For different format of records of input files, only need to modify RecordEntry.java

7. sample test files in the 



