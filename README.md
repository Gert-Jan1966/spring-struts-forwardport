## spring-struts-forwardport
A Spring 4.1.5 compatible spring-struts package

### Why a Spring 4.1.5 compatible spring-struts package?
I was required to use Struts 1.2.4 but I wanted to be able to utilize the latest version of Spring (4.1.5 at this moment).
Struts support has been deprecated since Spring 3.0.0 and disappeared since Spring 4.0.0. Unfortunately, I still needed this support.

### This code originates from the spring-struts 3.2.13 package
- The pom file has been reworked to reflect the Spring 4.1.5 dependencies. 
- Only the ContextLoaderPlugIn has been changed (just a tiny bit).
- I didn't need Tiles support, so all Tiles related classes and unittest have been discarded.
- Changed the Maven groupId and artifactId to reflect the fact that this is not a normal Spring package.
