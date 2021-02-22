# api-frontend-framework-test
This is  only for internal use for test purpose

**This is introduction about the framework and how to run it through the windows machine**

-> This framework is BDD Data driven framwork and internal structure is based on cucumber-selenium-testng for front end api test and cucumber with restassured for back-end tests
-> Build is supported by maven

Important folders
-> /src/test/java/stepDefinition - this is java package which contains glue code of cucumber features

+Two files are available in this folder, one is for frontend test and other is for back end test
+There are two test runner files are available to run seperate tests for front end and back end

-> /src/test/resources/features - this contains the frontend and backend cucumber files

->/src/main/java/test -  This is for creation of some utilities which i am using in current set up

->/src/main/java/resources - Currently taking the data from cucumber data table and hence not using it for external data reference

**Execution Steps-**
1. Upload the project in local
2. Navigate to /src/test/java/stepDefinition -> TestNGRunners*
3. Click on Run -> TestNG Runs

**Referral Results Video of Run**

1. https://www.screencast.com/t/GIpVtO5s - Backend video referal with results
2. https://www.screencast.com/t/jLSNmFNGx0 - Web Based Automation referal with results

Notes-
-> In this framework currently i am not using pojo class and pico container for rest api tests since data is small
-> There are some assumptions made on assignment given on steps
-> I have kept some default waits to give clear picture on its runs
-> I have used default reportings instead of Allure/testng Extent reports

