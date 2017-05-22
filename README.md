# ionic-2-push-notification
Push Notification in ionic 2 using FCM(Firebase Cloud Messaging).
For Setting Up.

1. Set up firebase base to get sender id.
Visit https://console.firebase.google.com and create new project.
Select Add firebase to your android app.
Input your package name(config.xml) and register your new app.
Go to Project setting(Near Overview) and select Cloud Messaging tab and copy your senders id.
Add sender id in app.component.ts.

2. Add plugin to your app. ionic plugin add phonegap-plugin-push --variable SENDER_ID="yoursenderidhere"
Check your config.xml for proper installing of plugin.

3. Install ionic native library for push notifications. npm install @ionic-native/push --save

4. To start push notifications in firebase console> project setting> notifications(left menu)> New Message (Select your relevent App)

