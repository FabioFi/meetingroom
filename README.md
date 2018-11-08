# meetingroom
Display meeting room
This is a tutorial to write a JavaScript single-page app to get Outlook mail, calendar, and contacts.
You can follow the full guide here: https://docs.microsoft.com/en-us/outlook/rest/javascript-tutorial

The only thing to change is your app ID

Register the app
New app registrations should be created and managed in the new Application Registration Portal to be compatible with Outlook.com.
https://apps.dev.microsoft.com

Head over to the Application Registration Portal to quickly get an application ID.

Using the Sign in link, sign in with either your Microsoft account (Outlook.com), or your work or school account (Office 365).
Click the Add an app button. Enter javascript-tutorial for the name and click Create application.
Locate the Platforms section, and click Add Platform. 
Choose Web, then enter http://localhost:8080 under Redirect URIs. 
Make sure that there is a check next to ALlow Implicit Flow.
Click Save to complete the registration. 
Copy the Application Id and save it. 

Open the outlook-demo.js file and replace "your code here" at the 6th row with your app ID.
