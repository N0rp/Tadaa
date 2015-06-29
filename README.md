# Tadaa

## Open in IntelliJ

* Open Intellij and have Gradle plugin installed
* Click on File>New>Project From Existing Sources
* Select build.gradle in the root directory

## Run

* Build with gradle: gradle build
* Download Jetty runner: wget http://repo2.maven.org/maven2/org/mortbay/jetty/jetty-runner/8.1.9.v20130131/jetty-runner-8.1.9.v20130131.jar
* Put jetty runner in root project directory
* Run web app with: 
* java -jar jetty-runner-9.1.0.M0.jar --port 8081 build/libs/Tadaa-1.0-SNAPSHOT.war
* Access in Browser with: http://localhost:8081/exy/example/some_text

## Maven 
[Maven Standard Layout](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html)

## Links
* Elastic Search Data taken from: https://github.com/cb372/elasticsearch-test-example
* Jetty Gradle Integration Test from: https://github.com/ziroby/jetty-gradle-hello-world and http://stackoverflow.com/questions/27889631/jersey-restful-web-service-gradle-setup
* Jersey: http://stackoverflow.com/questions/1495813/easiest-frameworks-to-implement-java-rest-web-services
* Jersey Hello World: http://www.mkyong.com/webservices/jax-rs/jersey-hello-world-example/