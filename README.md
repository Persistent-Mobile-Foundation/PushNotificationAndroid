# PushNotificationAndroid
Application that demonstrates use of Push Notifications feature

Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/notifications/

Usage
Import the project to Android Studio.
From a Command-line window, navigate to the project's root folder and run the command: pmfdev app register.
In the MobileFoundation console:
Under Applications → PushNotificationsAndroid → Security → Map scope elements to security checks, add a mapping for push.mobileclient.
Under Applications → PushNotificationsAndroid → Push → Push Settings, add Google Clout Messaging (GMC) Server API Key and Sender ID.
Run the app by clicking the Run button.
Sending a notification:

Tag notification
Use the Mobile Foundation Operations Console → [your application] → Push → Send Push tab.
Authenticated notification:
Deploy the UserLogin sample Security Check.
In MobileFoundation Operations Console → [your application] → Security tab, map the push.mobileclient scope to the UserLogin Security Check.
Follow the instructions for REST APIs to send the notification.
Notes:

The GCM Server Key and senderId values must be configured via the MobileFoundation Operations Console.
Supported Levels
PSL Mobile Foundation 9.0

