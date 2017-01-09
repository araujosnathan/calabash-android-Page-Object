# calabash-android-Page-Object
Using Page Object

For those who already know a little calabash is ideal when building our automation projects we use the Page Object approach, 
To know better you can access this link: https://developer.xamarin.com/guides/testcloud/calabash/xplat-best-practices/ 

Page Object is nothing more than representing each screen of the application as an object, 
in which it will have its elements and actions that can be performed in a given it. 

This way you can leave the generic commands in the steps of the features:

calabash-android-Page-Object/facebook_messenger/features/step_definitions/login_steps.rb

And use the calabash-android commands on screen objects that are created:

calabash-android-Page-Object/facebook_messenger/features/android/screens/

Why do that? 
It is ideal for code reuse for Android/iOS projects, both the android and iOS applications are supposed to have the same features, 
the steps will be the same, in this way the specifications / steps can be used on both platforms. 

The changes will be only the objects created, that is, the application screens 
(which will have their respective commands in Android/iOs calabash)

In this project it is shown how to use Page Object for an android project! 
To add the same project for iOS you will need to create only the objects for the iOS App Screens.

Do not just be a QA for one platform, you can be for both! Be smart!
