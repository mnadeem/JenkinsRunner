After downloading the zip file, create two folder tmp and logs under JenkinsRunnder (for some reason I am not able to push those two folders)
and copy your jenkins war file to JenkinsRunnder/lib

based on your environment start the appropriate script, you are done.

Configuration

If you want to change the port

Modify the JenkinsRunnder/conf/wrapper.conf file (line number 31) as follows

wrapper.app.parameter.2=--httpPort=8070