# Android-Appium-Calculator-App
## How to run this project
1. clone the project
2. Start the appium server
3. Connect mobile device with USB
4. Set the debug mode on from mobile device
5. Allow connection from phone
6. Make sure the phone is unlocked
7. Open **build.gradle** as project by intellIJ
8. Add configuration as:
    - a. Select TestNG as test runner
    - b. Give Test Name as **Run**
    - c. **Test Kind**: **Class**, **Class**: TestCase, **Use classpath as module**: **MyCalculatorApp.test**
9. Click on Ok button
10. Click Run button 

or 
give this command:
``` 
gradle clean test 
allure generate allure-results --clean -o allure-report
allure serve allure-results
```
![image](https://user-images.githubusercontent.com/87892957/134738328-c7c2960f-2b67-41ab-a0cb-34255cb11aff.png)
![image](https://user-images.githubusercontent.com/87892957/134738364-a39d6381-1fbf-4f68-9baf-173d987820e0.png)
