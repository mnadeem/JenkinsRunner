
# JENKINS RUNNER #
After downloading the zip file copy your jenkins war file to JenkinsRunnder/lib
based on your environment start the appropriate script, you are done.

---

### DIRECTORY DETAILS ###


* __data__ ==> contains files required for jenkins, configuration, jobs etc

* __logs__ ==> this where jenkins will spit out logs

* __conf__ ==> configuration that should be done to jenkins is driven through files in this folder

* __lib__ ==> this folder contains __wrapper.jar__ and __jenkins.war__, and any other jars you want to make available to classpath

* __bin__ ==> binary executables are present here, based on you environment you have to execute one of the files in this directory

---

### FAQ ###


##### How do I change the port? #####

__Modify the JenkinsRunnder/conf/wrapper.conf file (line number 31) as follows__

_wrapper.app.parameter.2=--httpPort=8070_

---
