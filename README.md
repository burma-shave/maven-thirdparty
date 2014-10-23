maven-thirdparty
================

A maven repo for various third party libs that I use.

Deployment example:

    mvn deploy -DaltDeploymentRepository=github-repo::default::file://path/to/maven-thirdparty

    mvn deploy:deploy-file -Dfile=sqljdbc4.jar -DgroupId=com.microsoft.sqlserver -DartifactId=sqljdbc4 -Dversion=4.0 -Dpackaging=jar \
    -Durl=file:///Users/ericj/software_development/tools/maven-thirdparty
