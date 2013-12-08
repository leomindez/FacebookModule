            Facebook Module for Android Studio
================================================================

This is a facebook module, you can add it in your android studio project. 

If you want to use this module for your projects you should follow the next steps:

* You should create a new libraries folder in your project root
* You should copy this project into the libraries folder, you must manually copy the project,because if you copy        it using the drag and drop action doesn't work the project because android studio throw an error
* Add the next line into settings.gradle file:
   include ':libraries:facebook'
* Add the next line into build.gradle file:
   compile project(':libraries:facebook')
* You should rebuild the project 

YOU MUST MODIFY local.properties file with your android sdk route
  

THAT'S IT!


