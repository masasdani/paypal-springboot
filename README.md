Paypal REST API Payment using Spring Boot
=========================================
This is sample project how to implement paypal rest api to spring boot web application,
if you see pom.xml it will show you that it's using spring boot 1.3.0 starter web, using thymeleaf as template engine, simple usage.

Prerequisites:
==============
*	Java JDK-1.7 or higher
*	Apache Maven 3 or higher
*	Please refer http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html for any help in Maven.

Usage
=====
to run this sample, please at first crete paypal account and register your apps to http://developer.paypal.com
change paypal configuration in src/main/resource/application.properties

		
		paypal.mode=sandbox
		paypal.client.app=xxxxxxxxxxxxxxxxxxYOUR_CLIENT_IDxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
		paypal.client.secret=xxxxxxxxxxxxxxxxxxYOUR_CLIENT_SECRETxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
		

Then run it using maven :

		
		maven spring-boot:run
		

Test in your browser : 

		
		http://localhost:8080
		

