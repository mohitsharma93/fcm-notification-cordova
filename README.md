## Now this is only for android. ##

## Prerequisites
* cordova 9.0.0
* android sdk or android studio
* java
* npm

## Download external softwares
* cordova : `https://cordova.apache.org/`
* android_sdk : `https://developer.android.com/`
* java: `https://www.java.com/en/download/`

## Installation
* get pull
* hit npm i

## Dependencies for apk
* i use cordova-plugin-fcm-with-dependecy-updated plugin to interact with firbase.

## Build process
* cordova build android 

## Documentation
* simple receive notification from fcm. through plugin.
* plugin needs google-services.json file to generate for your project. 
    01. got to `https://console.firebase.google.com/`
    02. sign in if not already.
    03. create your project (name it what ever you want), it will take some time.
    04. now you are on at fcm dash board, where you saw an ####android, ios, or <>#### icon.
    05. go to your config.xml you saw somthing like this (its on root of your folder).
       ``` <widget id="fcm.notification.cordova" version="1.0.0" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0"> '''
       here copy that id and go to your firebase console now  click on android icon 
            * paste id on Android package name filed (complete first step). and click on **Register app**
            * now download google-services.json file and replace it from my file.
            * skip next two step and go with next button
    06. now time to check over app is working or not.
    07. got to firebase console and search **Cloud Messaging** and click on it.
    08. find **send your first message**. and follow that steps.




## Steps
* cordova run --emulator (run on emulator if specified)
