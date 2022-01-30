# Data driven testing with Jmeter


# Introduction
This template will help you to implement a data driven testing framework. The most famous tool for performance testing are Jmeter & Gatling and we have used Jmeter in this template. So the template will basically help you to have an integrated data driven testing framework using Jmeter.

# What is data driven testing framework
A data driven testing framework is a technique in which you keep input test data separate from the actual test script.This DDT framework is totally dependent on the input test data. There are majorly two components in the data-driven testing framework. First is the test script and second test data.
The test data set is created in external sources such as an excel file, csv file, xml file, or any database (In this template we are using csv file) . After that we connect the test script with test data to retrieve multiple sets of data to perform the application under test.


# Technologies Used
Automation tool - Apache Jmeter

JAVA is prerequisite for Apache Jmeter so make sure that java should be installed.


# Steps for execution
Clone the repository on your local system.

Once you clone the repository, You will get two files
1. Test data(csv file)
2. .jmx file(plug and play jmeter script)

Open apache jmeter and import .jmx file which was cloned.

Click on "CSV data set config" under Test Plan and browse the Filename(path of test data file).

Now you are ready to execute performance testing on a dummy web application (https://blazedemo.com/login) with single data drived user.

To run the test click the green play button on toolbar.

Now you can see the test result on "View Results Tree" under the Thread Group.

We have used a dummy web application and csv test data in this template but you can change it accordingly. To change this project you only need to change variables, HTTP request and test data.

For a better understanding and changing this project according to you please refer to this blog based on same:-
https://blog.knoldus.com/data-driven-testing-in-jmeter/
