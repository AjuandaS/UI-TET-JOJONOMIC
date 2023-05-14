# UI-TET-JOJONOMIC

# Tech-Test-Jojonomic

Tools: Katalon Studio

Explaination:
Hello, here I will explain how to build automation to do UI and API testing for Tech Test at Jojonomic:
1. UI (User Interface) Testing
- Prepare website urls to be tested and also prepare test data in excel for data-driven, in this case search and suburb
- Then create testcases by scripting and creating variables according to the data in excel than import excel file with make Data file in Katalon Studio
- Make test suite for connet test case variable to test data from excel with Binding Data
- Then make a testing step in the Katalon script section by opening a web page, Search for "Apply for a number plate
- Click on Locate us button, Enter suburb "Sydney 2000" for this the search and suburb variables can be changed dynamically in the file excel for automated testing needs

2. API Testing
- Setting up an API endpoint to be tested and registered to get an API Key
- Open object repository and place endpoints and create variables according to testing needs such as lat, lon, key and postal_code
- Then create a new test case and create a variable according to the repository object and its value in the variable option
- then make a test step like: sendRequest for hit API then enter the variables, then get response then save it in the result variable, 
- then parse the response into json format and verify actual result with expected result that was initiate in variable one of the variables in this case lon and the test has been completed

3. How to run API test part A:
- Install Katalon Studio
- Download project API Test from Github
- Open Katalon Studio
- Open project and open API test project
- Open test case TC01-TestApiCurrent and Click Button play green color
- See the result of test on button section
4. How to run API test part B:
- Install Katalon Studio
- Download project API Test from Github
- Open Katalon Studio
- Open project and open API test project
- Open test case TC01-TestApiForcast and Click Button play green color
- See the result of test on button section
5. How to run UI test
- - Install Katalon Studio
- Download project API Test from Github
- Open Katalon Studio
- Open project and open UITestJojonomic project
- Open test suite TS01-UITest and Click Button play green color
- See the result of test on button section
- And we can see report on report folder and open in browser


Notes: For CI Integration (e.g circleCI) i've tried to integrated but for now Katalon CI integration is Paid for license and I'm not have money to buy the license.
