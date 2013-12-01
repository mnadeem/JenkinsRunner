
# JENKINS RUNNER #
After downloading the zip file copy your jenkins war file to JenkinsRunnder/lib
based on your environment start the appropriate script, you are done.

---

### DIRECTORY DETAILS ###


* data ==> contains files required for jenkins, configuration, jobs etc

* logs ==> this where jenkins will spit out logs

* conf ==> configuration that should be done to jenkins is driven through files in this folder

* lib ==> this folder contains wrapper.jar and jenkins.war, and any other jars you want to make available to classpath

* bin ==> binary executables are present here, based on you environment you have to execute one of the files in this directory

---

### FAQ ###


##### How do I change the port? #####

__Modify the JenkinsRunnder/conf/wrapper.conf file (line number 31) as follows__

_wrapper.app.parameter.2=--httpPort=8070_

---
