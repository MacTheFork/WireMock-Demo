# Demo of WireMock Standalone

includes PostMan collection to drive WireMock

Command to run WireMock standalone using at least Java 8

    java -jar wiremock-jre8-standalone-2.26.3.jar --local-response-templating --verbose


WireMock standalone jar

https://repo1.maven.org/maven2/com/github/tomakehurst/wiremock-jre8-standalone/2.26.3/wiremock-jre8-standalone-2.26.3.jar

Logging framework (no operation)

https://repo1.maven.org/maven2/org/slf4j/slf4j-nop/1.7.30/slf4j-nop-1.7.30.jar

Command to load an additional jar, in this case just to suppress SLF4J warnings

    java -classpath "wiremock-jre8-standalone-2.26.3.jar;slf4j-nop-1.7.30.jar" com.github.tomakehurst.wiremock.standalone.WireMockServerRunner --local-response-templating --disable-banner