## JENKINS RUNNER ##
![runnerImageId]

After downloading the zip file copy your jenkins war file to JenkinsRunnder/lib
based on your environment start the appropriate script, you are done.

Jenkins Runner is based on [Java Service Wrapper][jswId]
![Java Service Wrapper][jswImageId]


### FEATURES ###

---

* Pre bundled script which would allow you to manage jenkins instance in different environments seamlessly
* Configurations can be changed/added very easily
* Scripts supports init.d configuration and Windows Service modes
* Upgrading jenkins is just a matter of replacing __jenkins.war__ in lib folder
* Pre configured plugins can be provided with the bundle.
* you can added other jar files easily in the class path
* _application parameters_ and _jmv parameters_ can configured very easily



### DIRECTORY DETAILS ###

---


* __data__ ==> contains files required for jenkins, configuration, jobs etc

* __logs__ ==> this where jenkins will spit out logs

* __conf__ ==> configuration that should be done to jenkins is driven through files in this folder

* __lib__ ==> this folder contains __wrapper.jar__ and __jenkins.war__, and any other jars you want to make available to classpath

* __bin__ ==> binary executables are present here, based on you environment you have to execute one of the files in this directory



### FAQ ###

---


#### How do I change the port? ####

_Modify the JenkinsRunnder/conf/wrapper.conf file (line number 31) as follows_

	wrapper.app.parameter.2=--httpPort=8070



  [runnerImageId]: http://raw.github.com/mnadeem/JenkinsRunner/master/jenkins_logo.png  "Jenkins Runner"
  [jswId]: http://wrapper.tanukisoftware.com/  "Java Service Wrapper"
  [jswImageId]: http://wrapper.static.tanukisoftware.co.jp/images/jsw-logo.jpg "Java Service Wrapper"
