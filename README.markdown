Fenix Domain Broswer 
====================

Fenix Domain Browser is a webapp to inspect domains described in the Fenix Framework DML. 

Eclipse:
mvn eclipse:clean eclipse:eclipse

Compile the war:
mvn clean package

War generated on:
target/fenixDomainBrowser-<version>.war

Copy the war to your servelet server of your choise, like Jetty or Tomcat.

--------
isn't possible, for now, to run the application on dev using:
mvn gwt:run