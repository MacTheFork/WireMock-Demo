# Demo of WireMock Standalone

including PostMan collection to drive WireMock

## Installation
Download or clone this repository

Download the following WireMock standalone jar to the same location

https://repo1.maven.org/maven2/com/github/tomakehurst/wiremock-jre8-standalone/2.27.0/wiremock-jre8-standalone-2.27.0.jar

At a command line, use the following command to run WireMock standalone (needs a minimum of Java 8)

    java -jar wiremock-jre8-standalone-2.27.0.jar --local-response-templating --verbose



To add a logging framework (in this case just to suppress SLF4J warnings)

https://repo1.maven.org/maven2/org/slf4j/slf4j-nop/1.7.30/slf4j-nop-1.7.30.jar

Command to load an additional jar to the classpath

    java -classpath "wiremock-jre8-standalone-2.27.0.jar;slf4j-nop-1.7.30.jar" com.github.tomakehurst.wiremock.standalone.WireMockServerRunner --local-response-templating --disable-banner


#### Parts of a URL
    https://en.wikipedia.org/wiki/URL

#### JSON
    https://www.json.org

#### XML
    https://www.w3schools.com/xml/

    https://www.w3schools.com/xml/xml_soap.asp

#### Regex
    https://regex101.com/

