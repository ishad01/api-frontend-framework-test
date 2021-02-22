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

->/src/main/java/test and /src/main/java/resources - these folders contains few custom methods which are used in stepDefinition class

Execution Steps-
1. Upload the project in local
2. Navigate to /src/test/java/stepDefinition -> TestNGRunners*
3. Click on Run -> TestNG Runs

Note- 
In this framework currently i am not using pojo class for rest api tests since data is small
There are some assumptions made on assignment given on steps
I have kept some default waits to give clear picture on its runs
