## Prerequisites
* Ensure you have one of the following Java versions on the computer you are going to run the UA: 
  * Java JDK 8
  * Java JRE 8
  * Java JDK 11
* Additionally you need to have Gradle Package Manager installed 

## What to do?
* Download build.gradle to the computer you are going to run the UA
* Run the UA scan with '-logLevel debug' 

## Review
* Review the build.gradle. How many dependencies are there?
* Review the project created by the UA in WS UI. How many dependencies are there?
* Are there any vulnerabilities?
* Customer usually like to exclude test dependencies. Modify the config file so the scan results only reflect the dependencies that are going to be used in production.
