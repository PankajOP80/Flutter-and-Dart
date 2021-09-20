# Flutter
<p>A 'tool' tha allows you to build native cross-platform (IOS/ANDROID) apps with one programming language and codebase.</p>

![Image](Image\Screenshot_20210920-205735.jpg)
# Native Cross Platform
<p>(Native apps are developed exclusively for a specific platform. These apps are developed in a language compatible with the platform. Cross-platform apps are compatible with multiple platforms. Due to the market share of Android and iOS, most cross-platform apps are limited to these two operating systems.</p>



# The term flutter reffers to two major things
## **1.SDK(Software development kit)**
<p>Collection of tools that allows you too use one codebase with one programming language because it includes tools that compile this code which not usually run with IOS and Android into native machine code that does run with IOS and Android on these platform.. It not just a collection if tools also gives everything you need to create beautiful applications.. It gives you the framework, a widget library ford at one programming language which is called dart which is use to create beautiful Flutter apps.. It gives you the vast collection of Re-usable Ui building blocks (= widgets) things like button box taps text inputs drop-downs.. You can use them and customise them and then you build user interfaces with these tools.</p>



## **2.Dart**
<p>Dart is a programming language that focused on building front-end ( mobile apps, web) user interfaces development.. Dart is independent of flutter and you can also build web apps with dart... Flutter uses dart mostly for creating mobile apps. It is programming language  build to built really simple front end user interfaces... Its syntax is like a mixture of javascript, java ,c# (you dont need to know any of these languages to create application or to write code of dart)..</p>

![Image](Image\Screenshot_20210920-205746.jpg)

# Flutter vs Dart-
<p>Flutter builds up on dart its a framework for dart and dart is a programming languages which we are using... Flutter has dense collection of tools, features, utility function and widgets which are implemented using dart so that you dont have to reinvent the wielder and you can right your own dart code and use this existing widgets in your code  so that you dont have to again re-invent how buttons are look like and work but use the pre-built button instead and then just customize  to your requirements....</p>

![Image](Image\Screenshot_20210920-205807.jpg)

# Flutter Architecture

 <p>Flutter has the idea of building interfaces as code thats called UI as Code.. You build widget tree on your Flutter app.
 Flutter app do actually embrace platform differences while being base on one code so we work on one project and we still have the ability to create different interfaces at some points or in some parts of the app if we needed for the different platforms because Android and IOS are not exactly the same just for different phones they do have small differences and sometimes it doesn't matter to you but it does flutter gives you  the tools for find out which platform  you are running so that if you are on android you can execute code A and if you are on IOS you execute code B so flutter gives you the full flexibility there.</p>

![Image](Image\Screenshot_20210920-205817.jpg)

# Everything is widget
<p>In Flutter everything is widget. You build your entire app your entire screen with a widget. Actually whole page is widget. And even whole app is wrap in one main widget. And a widget you will see from here is the codes in this an instruction you place in your code....</p>

![Image](Image\Screenshot_20210920-205828.jpg)

# Your app's UI is a widget tree
<p>Your app is there for built as a widget tree... You have the root widget which is your app itself... Then you might have different screens there on the different screens you have different sections you might have text, inputs, outputs, buttons, tabs, dropdowns...</p>

![Image](Image\Screenshot_20210920-205834.jpg)

# One Codebase </>
<p>You will have bunch of dart files in your project and these will make your applications, you build an android and an IOS app based on one project.</p>

![Image](Image\Screenshot_20210920-222832.jpg)

# Embrace Platform Differences
<p>But as I mentioned you can find out which platform you are running and then render different content based on that platform.</p>

![Image](Image\Screenshot_20210920-205852.jpg)

# How is Flutter/Dart "transformed" to a native app
<p>You have your dart code which uses the flutter  framework or the flutter API whivh stands for Application Programming Interface it just means the Flutter gibes you the collection of functions, widgets ise in your code to built the interface you wanna build. So you have your own widgets amd your own code then composed that of set of build in-widgets, your own widgets. Now you wanna build for Android and IOS Flutter simply compiles that dart code to native code for these different platforms.. And that happnes with behalf of Flutter SDK and as a result you get real apps spit out with highly optimised high performance code that based on your code but thats not your code itself but that is compiled version of your code and therefore you really shift code that runs on the different platforms and  optimised a high performance. Because performance is the huge advantage of flutter apps. Flutter out of the box gives you a high performance applications.</p>

![Image](Image\Screenshot_20210920-205901.jpg)


---