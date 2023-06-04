Sample code to query User details in Azure Active Directory using Microsoft Graph APIs

1)Create a new tenant/directory if needed

2)Go to Azure Active Directory in the new tenant -- By default only 1 user will be there, let's create another one.

3)On left side menu of AAD, Go to App Registration--> New Registration

4)Inside the new created Registration -> Click on quickstart on left menu->Web Application--> Any Language(I did Java)

5)Configuration of application in portal which can be handled by Azure **(Very Imp - Note the Client Secret Value as it can't be seen again)**

6)Create a simple maven project like this and add the dependencies.

7)Take the client id, tenand id from overview portal of that registered app

8) Replace client id, tenand id and clientSecret(step 5) and run the code.

9) You should see 2 users names.
