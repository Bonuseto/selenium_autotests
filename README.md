# Automation test with Selenium and Python 

This is an example project demonstrating automation testing using selenium and python. It is also using POM (Page object model) pattern framework

**Application Under Test**

URL : https://www.saucedemo.com/


**Scenarios**
```
Scenarios 1 : Login Tests
Scenarios Description: Test login function with many types of account: standard, problem, performance_glitch_user, locked_out_user and invalid user
Test name: LoginTest.py
```

```
Scenarios 2 : Smoke tests
Scenarios Description: Verify all elements of application such as : Logo, input fields, titles, buttons is visible and enable on the Login and Home page
Test name: SmokeTest.py
```

```
Scenarios 3 : Link tests
Scenarios Description: Verify all links of application such as : 
Test name: LinksTest.py
```

```
Scenarios 4 : Detail page tests
Scenarios Description: Verify all images, titles, prices, and detail of items. 
Test name: DetailPageTest.py
```

**Installation**

Clone the repository
```
git clone https://github.com/Bonuseto/selenium_autotests.git
```
Come to the test cases folder

```
cd POM/testCases
```

Run all test cases
```
py -m runTestCases.py
```
