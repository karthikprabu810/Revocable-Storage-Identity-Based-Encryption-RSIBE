Language used: JS and php

Readme

Download link shared below
1)JDK 18 (windows)
https://download.oracle.com/java/18/latest/jdk-18_windows-x64_bin.exe
2)Apache net-beans 13 (windows)
https://archive.apache.org/dist/netbeans/netbeans-installers/13/Apache-NetBeans-13-bin-windows-x64.exe
other installers and files are included in the repo
3) MySQL installer
https://downloads.mysql.com/archives/get/p/23/file/mysql-8.0.28-winx64.zip
4) Tomcat
https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.62/src/apache-tomcat-9.0.62-src.zip
5)VC_redist
https://www.microsoft.com/en-in/download/confirmation.aspx?id=48145



01. Download Softwares
02. Install JDK
03. Install netbeans
04. Install VC_redist
05. Install mysql installer
06. In mysql installer install(server,workbench,connector j) and configure local server
07. Download and extract Tomcat
08. Change Tomcat Server (add lines under connector port of HTML)
09. Extract SecureDataSharing_Required_Working_31052022 zip
10. Open netbeans and Open project
11. Add Server to netbeans
12. Search->Project Properties -> Run -> JDKv8 binary format
13. Extract javax.xml.bind.jar
14. Search->Project Properties -> Libraries -> Add JAR -> javax.xml.bind.jar.
15. Open MySql configure and open local server
16. Open SecureDataSharing sql file in DB folder
17. Open netbeans -> files -> getcon
18. Configure URL(localhostid),USR(username),PASSWORD(password)
19. Clean, Build and Run Project
20. Enter server username and password when prompted