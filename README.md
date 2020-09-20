# Level 1 Questions

## What are the names of the latest three versions of Android?

- Android 10
- Android Pie
- Android Nougat
 
## What does the abbreviation ART stand for?
 **Android** Runtime (**ART**) **is** an application runtime environment used by the **Android** operating system.

## What is Android Jetpack?
A suit of libraries to help developers follow best practices, reduce boilerplate code, and write code that works consistently across **Android** versions

## Describe the difference between the fixed, wrap_content and match_constraint setting of the constraint layout?

 - wrap_content will set the width or height to be set to wrap the content
 - fixed will set the content to a contant width or height
 - match_contraint will set the width or height to be equal to the width or height of the screen.

## What does the abbreviation DP stand for and why do we need them?
Android devices come in different sizes and have there for different size of pixels on their screen, that is why DP is used. These are resolution-independent units of measurements and provide alternative bitmap resources for each pixel density.

## What is the purpose of the string.xml file?
The purpose of this file is that it serves as a single resource that provides strings

## Why is the layout in Android specified by .xml files? Why not just have the layout in the code (Kotlin or Java)?
Declaring your UI in XML allows you to separate the presentation of your app from the code that controls its behavior. Using XML files also makes it easy to provide different layouts for different screen sizes and orientations

## What kind of information can be found in the manifest file?
The manifest file describes essential information about your app to the Android build tools, the Android operating system, and Google Play.

## What is the purpose of view binding in Android?
**View binding** is a feature that allows you to more easily write code that interacts with **views**. Once **view binding** is enabled in a module, it generates a **binding** class for each XML layout file present in that module.

## Describe how you can log the value of variables in the Android Studio system log, and how you can find them back.
There's a API for loggin with the Log class. These logs can be found in the Logcat.

## Describe how you can debug your app in Android Studio, e.g. by setting breakpoints and inspecting the value of variables.
Your code can have some errors while building a new feature, so if you set a breakpoint on the line that you want to inspect it can help you find and understand what is going on. After setting a breakpoint on the line that is going to be inspected, the bug icon has to be pressed to run de debug mode.
