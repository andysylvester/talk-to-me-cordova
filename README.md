README.md
=========

Overview
--------

This is an Cordova application for Android that demonstrates text-to-speech features.

The design is taken from the MIT App Inventor app "Talk to Me" developed for the Hour of Code
project (http://appinventor.mit.edu/explore/ai2/beginner-videos.html). This app allows the
user to enter text into a text box. When the button is clicked, the text is spoken by the
Android device and vibrates for two seconds.

The basic structure for the application is based on the HelloWorld4 application from
John Wargo's book "Apache Cordova 3 Programming". The source code for that application
is available on GitHub at https://github.com/johnwargo/cordova-programming-code/tree/master/chapter05/helloworld4

Prerequisites
-------------

* A current installation of Apache Cordova (http://cordova.apache.org)
* An Android device (phone or tablet)

Installation
------------

* Get a copy of this repository
* Create a new Cordova project directory at the command line ("cordova create TalkToMe")
* Enter the directory ("cd TalkToMe")
* Add the Android platform ("cordova platform add android")
* Add the following plugins:
* "cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-dialogs.git"
* "cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-vibration.git"
* "cordova plugin add https://github.com/macdonst/SpeechSynthesisPlugin"
* Copy the www directory and the config.xml file from the repository to your project directory, overwriting the default files
* Build the application ("cordova build android")
* Connect your Android device to your computer, then run the application ("cordova run android")

The application should open on your device and show a text field and button.

You can click the button to speak the default phrase ("Hello world"). To enter a different phrase, tap in the text field
and enter some text in the field. Do not enter any punctuation, this can keep the text from being read.

Here is a picture of the finished app:

<img src="http://andysylvester.com/wp-content/uploads/2014/02/Screenshot_TalkToMe.png" height="300" width="200">

This <a href="http://andysylvester.com/2014/02/08/first-steps-with-cordova-talk-to-me/">blog post</a> also talks about the app.

 