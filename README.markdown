Fenix Domain Browser 
====================

Fenix Domain Browser is a webapp to inspect domains described in the Fenix Framework DML. 


### Eclipse 
`mvn eclipse:clean eclipse:eclipse`

### Compile the war:
`mvn clean package`

### War generated on:
`target/fenixDomainBrowser-<version>.war`
Copy the war to your servelet server of your choise, like Jetty or Tomcat.
Run it.

### Operating System
Code is dependent on graphviz. The dot command must be on "/usr/bin/dot". 

### Objectives to the future:
Replace the graphviz with the yuml.me or other online uml tool.
Run this app on Google App Engine.