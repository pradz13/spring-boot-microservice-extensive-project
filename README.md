# spring-boot-microservice-extensive-project

SDKMan set up
=============
Install SDKMan with the following command -
curl -s "https://get.sdkman.io" | bash

After installation, run the following command to list the available SDKs
sdk list java

Install a JDK with the command -
sdk install java <jdk name>

The configuration is available in the following file -
cat ~/.sdkman/etc/config

Update the following config to true
sdkman_auto_env=true

Add .sdkmanrc file with java and maven version

Maven Wrapper Set up
=====================
Maven wrapper helps when there in no Maven installed in the machine where the maven commands need to be run.

Run the command -
mvn wrapper:wrapper

Run the maven command like-
./mvnw clean package