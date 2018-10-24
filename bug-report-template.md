## Defect report template :bug:
An effective defect report template to raise a bug.

### Summary:
How would you describe the bug in less than 60 characters? It should quickly and uniquely identify a bug report as well as explain the problem, not your suggested solution.

      Good: "Login failed with Invalid credential message"
      Bad: "Invalid credential"

### Component/Feature:
In which sub-part of the software does it exist?

       Example: Registration, Dashboard or Payment


### Application Name, Version and Build Id:
Provide the application version with what the problem can be reproduced. And Build Id if applicable.

        An example would be: App Store, Version 2.2 and Build Id 580.11

### Environment:
On which test has been executed.

       Such as Test, Staging/Sandbox, Production.

### Device type:
 On which Device did you find it?

       Example: Laptop, Tablet, Mobile, Smartwatch, SmartTV or eBook readers.

### OS:
On which operating system (OS) did you find it? (e.g. Linux, Windows XP, Mac OS X.)

       Example: "If you know the bug happens on more than one type of operating system, provide the list.

### Browser:
    On which Browser did you find it? Also provide browser version.

### Description:

This is a larger detailed restatement of the summary.

       An example would be: "Login failed with Invalid credential message when login with valid username & password".
       test data used:
       1) username: John
       2) password: Doe
       3) email: john.doe@test.com
       4) client: Acme


### Steps to Reproduce:
Minimized, easy-to-follow steps that will trigger the bug. If they're necessary, make sure to include any special setup steps. An example would be:

      1. Click on the login button, a page with login form will appear.
      2. Enter the valid username and password (from test data) and submit.

### Actual Results/Behavior:
What the application did after performing the above steps.

        An example would be: Login failed.

### Expected Results/Behavior:
What the application should have done, were the bug not present.

       An example would be: After a successful login, user should be redirected to dashboard.

Sources:

[Bug writing guidelines](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Bug_writing_guidelines)
