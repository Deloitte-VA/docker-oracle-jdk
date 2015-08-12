# docker-oracle-jdk
CentOS with Oracle install for running java applications in the Deloitte VA systems

## Usage instructions
* For usage as a dependency, add <pre>FROM deloitteva/docker-oracle-jdk:version</pre>, replacing the word "version" with the version that you would like to use.  For a list of possible versions, please check out the [versions on DockerHub](https://registry.hub.docker.com/u/deloitteva/docker-oracle-jdk/tags/manage/)
* For execution instructions, please visit [DockerHub](https://registry.hub.docker.com/u/deloitteva/docker-oracle-jdk/)

## Release instructions
* Create a branch of the version that matches the tomcat version you are attempting to release.  This would be something like "8.0.23".  
* Go to [DockerHub](https://registry.hub.docker.com/u/deloitteva/docker-oracle-jdk/) and add an automated build for this new branch/version.
* Once it has completed building, it should be available for use.
