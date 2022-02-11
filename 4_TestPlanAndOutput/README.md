##  High Level Test Plan

|**Test ID**|**TestCaseScenario**|**TestCase**|**PreCondition**|**TestSteps**|**TestData**|**ExpectedResults**|
|----|----|----|----|----|----|----|
|H_01|Verify the login of Mail|Enter valid username and user password| Need a valid Mail to login|Enter username & Password, Click login|Valid username Valid password|Successful login|
|H_02|Verify the login of Mail|Enter valid username and invalid password|Need a valid Mail to login|Enter username & Password, Click login|Valid username invalid password|The mail and password you entered don't match|
|H_03|Verify the login of Mail|Enter invalid username and valid password|Need a valid Mail to login|Enter username & Password, Click login|invalid username Valid password|The mail and password you entered don't match|
|H_04|Verify the login of Mail|Enter invalid username and invalid password|Need a valid Mail to login|Enter username & Password, Click login|invalid username invalid password|The mail and password you entered don't match|


## Low Level Test Plan
|**Test ID**|**TestCase**|**TestData**|**ExpectedResult**|
|----|----|----|---|
|L_01|Enter valid username and user password|valid username valid password|Successful login|
|L_02|Enter valid username and invalid password|Valid username invalid password|The mail and password you entered don't match|
|L_03|Enter invalid username and valid password|invalid username valid password|The mail and password you entered don't match|
|L_04|Enter invalid username and invalid password|invalid username invalid password|The mail and password you entered don't match|
