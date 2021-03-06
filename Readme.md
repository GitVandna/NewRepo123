# Selenium-Cucumber-Java
--------------
selenium-cucumber : Automation Testing Using Java

selenium-cucumber is a behavior driven development (BDD) approach to write automation test script to test Web.
It enables you to write and execute automated acceptance/unit tests.
It is cross-platform, open source and free.
Automate your test cases with minimal coding.
[More Details](http://seleniumcucumber.info/)

 # Pre-requisites
- [Java](https://java.com/en/download/manual.jsp)
- [Maven](https://maven.apache.org/download.cgi)
- [Eclipse](https:https://eclipse.org/downloads/)

# Setting up Selenium-Cucumber-Java
- Install Java and set path
- Install Maven and set path
- Clone respective repository


# Writing a test
--------------

The cucumber features goes in the `features` library and should have the ".feature" extension.

You can start out by looking at `features/my_first.feature`.

# Running test
--------------

Go to your project directory from terminal and hit following commands
* `mvn test (defualt will run on local firefox browser)`
* `mvn test "-Dbrowser=chrome" (to use any other browser)`
* `mvn test "-Dcloud_config=saucelab_windows_chrome52" (to run test on cloud test platforms)`
