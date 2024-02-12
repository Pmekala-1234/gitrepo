**MavenGithub Project**

**Overview**

This repository cantains in Maven Project to test the Sample Website called -https://www.saucedemo.com/ with structure of BDD framework containing various depencencies,Packages,Classes anf Files and aTest Runner

**Saucedemo.com** -https://www.saucedemo.com/

![Screenshot 2024-02-11 092841](https://github.com/Pmekala-1234/gitrepo/assets/156926595/d927dff0-2487-452e-9d3c-d62b5c022eaa)

This is a sample test automation framework.SauceDemo is a sample website built by SauceLabs that allows users to practice browser automation.

Many Selenium tutorials online show:

How to load a page

How to select elements

How to interact with elements

**Why saucedemo.com?**

Saucelabs is a reputable automation testing platform company. It is likely to remain online without being taken down, allowing this demo to be viewed and run by others. This website was built to be automated against. Saucedemo.com is reliable and quick which leads to few false positive test failures.

**What do these tests cover?**

These tests cover many test cases such as signing in/out, adding items to the cart, and checking out.

**What isn't tested?**

Layout issues, sessions, cookies, APIs, etc.

**What do I need to run this example?**

IntelliJ - https://www.jetbrains.com/idea/download/?section=windows
Java - https://www.java.com/download/ie_manual.jsp
Maven - https://maven.apache.org/download.cgi


Under IntelliJ with BDD Framework :

projescts
packages - project/src/test/java
classes - project/src/test/java/packages/classes
files - project/src/test/java/packages/files
TestRunner - project/src/test/java

![Screenshot 2024-02-11 104521](https://github.com/Pmekala-1234/gitrepo/assets/156926595/8c491c10-74e3-4017-be69-817336819853)

**Dependencies**

Dependencies to be added to pom.xml(project\pom.xml)

![Screenshot 2024-02-11 110855](https://github.com/Pmekala-1234/gitrepo/assets/156926595/0df0d48d-e63e-408a-b7e6-eec4356767b8)

Junit 

Selenium WebDriver

Cucumber

Cucumber Junit


**Process**

After cloning the respository to local PC ,open the repository , Then in IntelliJ build the Code for respective Functionality to be tested and Run the Test using Runner Class or Maven Terminal or Command line

![Screenshot 2024-02-04 181104](https://github.com/Pmekala-1234/gitrepo/assets/156926595/e8776f7a-e6ef-4843-b4ad-4d9398030004)

**Report**

Once the Test is executed seccessfully a Cucumber Report can be generated from target file (project/target/cucmber.html) using  cucumber plugins.


![Screenshot 2024-02-10 115827](https://github.com/Pmekala-1234/gitrepo/assets/156926595/bf0ccb3b-29ee-43ca-b325-3b020b6ef4c5)













