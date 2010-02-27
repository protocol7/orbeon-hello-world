Before you can build this sample, you need to install the orbeon-xforms-filter into your local Maven repo:

    mvn install:install-file -DgroupId=orbeon -DartifactId=orbeon-xforms-filter -Dversion=3.7.1 -Dpackaging=jar -Dfile=/path/to/exploded/orbeon.war/WEB-INF/lib/orbeon-xforms-filter.jar

After that, you should be able to build this project using:

    mvn package

And install the generated WAR into the Tomcat in which you installed Orbeon. Now, access http://localhost:8080/orbeon-play/test/test.html and you should see your form.