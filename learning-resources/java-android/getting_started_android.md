##Welcome to the Android Hack Night Getting Started Guide##

_If you are brand new to Android, we recommend coming to the first meeting of the month which is **First-Timers Night**.  You are welcome to come any week, but that first week will be the one when we cater to beginners._

**Table of Contents**
* <a href="#SuggestedCourses">Suggested Courses</a>
* <a href="#WhatsAndroid">What is Android?</a>
* <a href="#AndroidUses">What is Android used for?</a>
* <a href="#AndroidTools">Which tools do I need?</a>
* <a href="#PhoneNotNeeded">Do I need a phone to make Android apps?</a>
* <a href="#InstallJava">What should I do first? (Install Java)</a>
* <a href="#InstallAS">Now what? (Install Android Studio)</a>
* <a href="#InstallPackages">Install Necessary Packages</a>
* <a href="#SetupPhone">Setup your phone/tablet</a>
* <a href="#HelloAndroid">Hello, **~~World~~** Android!</a>
* <a href="#InstallFasterEmulator">Install a Faster Emulator</a>
* <a href="#Sharing">Sharing your app with others</a>
* <a href="#PutAppInStore">Putting your app in the Google Play or Amazon App Stores</a>
* <a href="#InexpensivePhones">Where to buy inexpensive Android phones</a>
* <a href="#OnlineCourses">Online Android Courses</a>
* <a href="#AndroidResources">Android Resources</a>
* <a href="#JavaResources">Java Resources</a>
* <a href="#IDEs">Additional IDEs</a>
* <a href="#Help">Get Help</a>
* <a href="#Challenges">Challenges and Projects</a>
* <a href="#KeepInTouch">Keep in Touch</a>

###<a name="SuggestedCourses">Suggested Courses</a>###

If you are brand new to coding - [Udacity's Android for Beginners](https://www.udacity.com/course/android-development-for-beginners--ud837)    
If you are new to Android, but have coded before - [Udacity's Developing Android Apps](https://www.udacity.com/course/developing-android-apps--ud853)

###<a name="WhatsAndroid">What is Android?</a>###

Android is a software stack for mobile devices that includes an operating system, middleware, and key applications. The Android Software Development Kit (SDK) provides the tools and Application Programming Interfaces (APIs) necessary to begin developing applications on the Android platform using the Java programming language.  You should know the basics of Java programming before starting your Android journey.  A good course to learn enough Java to prepare for Android programming is Udemy’s [Become an Android Developer From Scratch](https://www.udemy.com/become-an-android-developer-from-scratch/) course.  More <a href="#JavaResources">Java resources</a> can be found at the end of this document.

###<a name="AndroidUses">What is Android used for?</a>###

Android is used for making applications (apps) that run on Android devices.  This includes Android smartphones, smartwatches (Android Wear), and anything else that runs on the [Android operating system](https://developer.android.com/about/index.html) (OS) like [Andorid Wear](https://developer.android.com/wear/index.html), [Android TV](https://developer.android.com/tv/index.html), and [Android Auto](https://developer.android.com/auto/index.html).  Once developed, Android applications can be packaged easily and distributed or sold either through a store such as Google Play or the Amazon Appstore.

###<a name="AndroidTools">Which tools do I need?</a>###

You can write Android programs on PCs, Macs, and Linux machines.  This is unlike writing apps for iOS devices which can only be done on Macs legally.  You’ll need a piece of software called an IDE (Integrated Development Environment).  Android Studio is now the official IDE for Android, which we recommend.  It’s a free download and works on all platforms. Although there are other IDEs available to use with Android, such as Eclipse and IntelliJ, we are hoping to steer everyone towards Android Studio as that is the platform fully supported by Google, the developer of Android,  moving forward.  You will also need both the Java Development Kit (JDK) and the Android SDK.  Note:  the JDK is different than the JRE (Java Runtime Environment) which allows people to run Java programs.  We need the JDK to be able to write Java programs.

###<a name="PhoneNotNeeded">Do I need an Android phone/tablet in order to make an app?</a>###

No!  Though it sure is fun to put the apps you make on your own device.  The Android SDK includes a mobile device emulator — a virtual mobile device that runs on your computer. The emulator lets you develop and test Android applications without using a physical device.  There are other emulators like genymotion which we will discuss later.

###<a name="InstallJava">I'm ready to get started.  What should I do first?</a>###

Check to see that you have JDK 7 or JDK 8 on your computer.  

* **Windows**:  visit [https://www.java.com/verify/](https://www.java.com/verify/) to check to see if the JDK is already installed on your machine.  Remember this is the JDK, not the JRE.

* **Mac/Linux**:  open a terminal window and type "which javac".  If something appears, then you have a version of the Java JDK on your machine.  If you’d like to know which version of Java you have, type “javac -version”.

* If you don’t have Java on your machine, install the JDK by visiting [Oracle’s website](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and downloading the most recent version of the Java SE 7 that is appropriate for your machine.

###<a name="InstallAS">Okay, I’ve got Java.  Now what?</a>###

Now it’s time to download the most recent version of Android Studio, the official Android IDE.  Visit [http://developer.android.com/sdk/index.html](http://developer.android.com/sdk/index.html) to get the software appropriate for your operating system.

**To set up Android Studio on Windows:**

* Launch the .exe file you just downloaded.

* Follow the setup wizard to install Android Studio and any necessary SDK tools. (If you are new to Android Studio, you can’t go wrong with installing with default settings - you can always add additional packages later.)

**To set up Android Studio on Mac OSX:**

* Launch the .dmg file you just downloaded.

* Drag and drop Android Studio into the Applications folder.

* Open Android Studio and follow the setup wizard to install any necessary SDK tools.

* Depending on your security settings, when you attempt to open Android Studio, you might see a warning that says the package is damaged and should be moved to the trash. If this happens, go to System Preferences > Security & Privacy and under Allow applications downloaded from, select Anywhere. Then open Android Studio again.

If you need to use the Android SDK tools from a command line, you can access them at:  /Users/<user>/Library/Android/sdk/.

**To set up Android Studio on Linux:**

* Unpack the downloaded ZIP file into an appropriate location for your applications.

* To launch Android Studio, navigate to the android-studio/bin/ directory in a terminal and execute studio.sh.

* You may want to add android-studio/bin/ to your PATH environmental variable so that you can start Android Studio from any directory. (Ex: `export PATH=$PATH:~/your_android_directory/android-studio/bin`) [For more info, see this guide.](http://www.codeproject.com/Articles/802813/Setting-Up-Android-Development-Ubuntu)

* Follow the setup wizard to install any necessary SDK tools.

**Ensure that you have the most recent version of Android Studio:**

After launching Android Studio, select the check for updates option in the toolbar. 

###<a name="InstallPackages">Wait, there's more!  Time to install packages.</a>###

Android Studio doesn't work right out of the box, so we will have to install some additional packages in order to make it run properly.  Here are the ones we recommend; you can always add additional packages or delete unnecessary ones later.

* Open Android Studio.
* On the Welcome menu, click on _Configure_.
* Select _SDK Manager_.
* In the window that opens, select the following packages:
  *  Tools - this should select all items in that category.
  *  Android 4.4.2 (API 19) 
  *  In the Extras category:  Android Support Repository, Android Support Library, Google Repository, and Google USB Driver
* Select _Install Packages_.
* Accept License Agreement.
* Grab your favorite beverage or book to read; this is going to take a while.  

###<a name="SetupPhone">Let’s take the time to set up your phone.</a>###

Now is a good time as any to set up your phone/tablet if you have one. emember, you can build and test many apps with just the built-in emulator, so the connected phone/tablet is just a bonus.  You have to do four things to enable testing of your apps on your device:

* Ensure your phone will allow the installation of apps from unknown sources (the unknown source is you rather than apps from the Play Store.)  Try looking under Settings → Security and make sure the checkbox for _Unknown Sources_ is checked.

* Turn on _Developer Options_ under Settings if that option isn't currently available.  To do this, go to About Phone, find the build number, and click on it several times until it unlocks Developer Options.

* Allow _USB debugging_.  Try looking under Settings → Developer Options and check the USB debugging box.

* Connect your Android phone to your computer via a cable.

###<a name="HelloAndroid">Hello, **~~World~~** Android!</a>###

It’s time to check to see if everything has been installed and is working properly.  We will make a simple Hello World app.  Try this [tutorial](http://www.techotopia.com/index.php/Creating_an_Example_Android_App_in_Android_Studio) or follow these directions:
* Open Android Studio.
* On the Welcome menu, click on _Start a New Android Studio Project_.
* In the window that opens, you'll have to supply your new app's info:
  * _Application Name_ is the app name that will appear to users.  Try using, "My First App" for this project.
  * _Company Domain_ is the name of your company or group, something like "yourname.example.com".  This is used to automatically generate the package name below this field.  This is the package namespace for your app.  Your package name must be unique across all packages installed on the Android system. For this project, you can use something like the example. However, you cannot publish your app on Google Play using the "com.example" namespace.
  * _Project Location_ can be left with the default path unless you desire an alterate folder for your project.
  * _Minimum Required SDK_ is the lowest version of Android that your app supports, indicated using the API level.  It's a good idea to leave it at the default value for this project.  Note:  Android 5.0 (Lollipop) is not widely used yet, so Android 4.4 (KitKat) is a safer bet.  Click Next.
  * Leave Phone and Tablet checked, and leave Minimum SDK at the default. This indicates the lowest version of Android (also using the API level) with which you have tested with your application. Click Next.
  * Leave Blank Activity selected and click Next.
  * Leave all the details for the activity in their default state. Click Finish.
  * Android Studio may take a minute or two to set up and then open your project. On Windows, allow any requests for Internet access you are prompted for.
  * To test your app, hit the run button (looks like a green play button).  
  * If there are no errors, you will be prompted to run on a specific device or on an emulator.  If your device is plugged in and drivers are loaded, it should show up in the list.  If it doesn't, you might have to install the driver for your phone from the manufacturer's website.
  
###<a name="InstallFasterEmulator">How to install a faster emulator</a>###

[Genymotion](http://www.genymotion.com/) is an incredibly fast, memory-efficient VM that runs the Android OS in a more accurate manner than even the official emulator.  Many Android developers do all their device testing using this emulator especially when Google Play services is concerned.  In addition, the official Android emulator is plagued with a lot of bugs (i.e. intermittent network loss) that Genymotion is usually a far more reliable option.  [Start here](https://github.com/codepath/android_guides/wiki/Genymotion-2.0-Emulators-with-Google-App-support).

> **_Linux installation of the genymotion package -_** After downloading the .bin file, move the .bin file where you would like to access genymotion from (suggested /home/username/Android/). Within that directory, type: chmod +x genymotion-*versionNumber*.bin to unpack genymotion. Remember what directory genymotion is in; you will need to know this when installing the plugin in Eclipse/Android Studio!  The[ plugin installation directions](https://www.genymotion.com/#!/download) on genymotion.com are otherwise pretty clear.

###<a name="Sharing">How to share your app with others</a>###

Once you have your app in a place where you wish to share it, you can package your app by creating a [signed APK (Android application package)](https://www.udacity.com/wiki/ud853/course_resources/creating-a-signed-apk) file.  Once this file is created, you can give it to anyone you want who has an Android phone.  An easy way to transfer the file is to send it to someone’s Gmail account as an attachment.  When they open the email from their phone, an option to download and install the app shows up right away.  Easy breezy!

###<a name="PutAppInStore">How to put your app in the Google Play Store</a>###

* Register for a [Publisher Account](http://developer.android.com/distribute/googleplay/start.html) and pay the one-time $25 account fee.  This will allow you to publish an unlimited amount of apps.

* Complete the [launch checklist](http://developer.android.com/distribute/tools/launch-checklist.html).

* Share your success by letting WomenWhoCode DC know that you published an Android app!

###<a name="InexpensivePhones">Where to buy inexpensive Android phones</a>

* [FreedomPop - $24.99](https://www.freedompop.com/offer/zte2499promo?utm_source=affiliate&utm_medium=slickdeals&utm_campaign=zte2499promo&sdtid=7609918)
  
###<a name="OnlineCourses">Online Android Courses</a>###

Some older resources use Eclipse, but similar features are available in Android Studio.

* All Android Studio

  * [Become an Android Developer from Scratch](https://www.udemy.com/become-an-android-developer-from-scratch/?dtcode=TPTbIQE29HVW) (paid - Udemy, course is often $10)
  * [Developing Android Apps](https://www.udacity.com/course/ud853) (free - Udacity)
  * [University of Reading Beginner Tutorial](https://www.futurelearn.com/courses/begin-programming) (free)

* Some Eclipse/ Some Android Studio

  * [The Complete Android Lollipop Development Course](https://www.udemy.com/android-lollipop-complete-development-course/) (paid - Udemy) - starts with Eclipse IDE, moves to Android Studio, teaches java along the way

* Eclipse

  * [Coursera Android Specialization](https://www.coursera.org/specialization/mobilecloudcomputing2/36?utm_medium=listingPage) (free) - videos from 2013/early 2014, four week courses start ~monthly
  * [Coursera Sequence](https://www.coursera.org/specialization/mobilecloudcomputing2/36?utm_medium=listingPage) (free) - uses Eclipse in video
  * [How to Program for Beginners](http://www.linux.com/learn/docs/683628-android-programming-for-beginners-part-1)[ (free)](http://www.linux.com/learn/docs/683628-android-programming-for-beginners-part-1)
  * [Beginner Coursera](https://www.coursera.org/course/androidapps101)[ (free)](https://www.coursera.org/course/androidapps101)
  * [Lynda.com](http://www.lynda.com/Android-tutorials/Building-Note-Taking-App-Android/122466-2.html) - get free access with DC or Arlington library card! (http://www.lynda.com/Android-tutorials/Building-Note-Taking-App-Android/122466-2.html)

###<a name="Android Resources">Additional Android Resources</a>###

* Android Tutorials

  * [Codepath](https://github.com/codepath/android_guides/wiki)
  * [TutorialsPoint](http://www.tutorialspoint.com/android/android_tutorial.pdf)

* Android Books

  * [Big Nerd Ranch](http://www.bignerdranch.com/we-write/android-programming.html)

* Android Bootcamps

  * [Code Path Evening Bootcamp ](https://codepath.com/androidbootcamp)(8 weeks)
  * [Big Nerd Ranch Bootcamp](https://training.bignerdranch.com/classes/android-bootcamp) (1 week)

###<a name="JavaResources">Java Resources</a>###

* Courses

  * [Java for Complete Beginners (Udemy)](https://www.udemy.com/java-tutorial/)
  * [Stanford University’s Introduction to Java](http://see.stanford.edu/see/courseinfo.aspx?coll=824a47e1-135f-4508-a5aa-866adcae1111)
  * [A Bachelor’s Level Computer Science Curriculum](http://blog.agupieware.com/2014/05/online-learning-bachelors-level.html)
  * [Intro to Programming Udacity: Java](https://www.udacity.com/course/cs046)
  * [MIT’s Introduction to Programming in Java](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-092-introduction-to-programming-in-java-january-iap-2010/)
  * [Coursera Introduction to Android Programming](https://class.coursera.org/android-001/lecture)
  * [Intro to Programming](http://www.saylor.org/courses/cs101/)
  * [Virtual Pair Programmers](https://www.virtualpairprogrammers.com/training-courses/Java-Fundamentals-training.html)

* Books

  * [Head First Java](http://www.amazon.com/Head-First-Java-2nd-Edition/dp/0596009208/ref=sr_1_1?ie=UTF8&qid=1400022857&sr=8-1&keywords=head+first+java)
  * [Java: How to Program, 9th Edition (Deitel)](http://www.amazon.com/Java-How-Program-Edition-Deitel/dp/0132575663)
  * [Effective Java](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)

* Exercises and Tutorials

  * [Coding Bat Java Exercises](http://codingbat.com/java)
  * [Coderbyte Java Exercises](http://www.coderbyte.com/CodingArea/Challenges/)
  * [Tutorialspoint Java Guides](http://www.tutorialspoint.com/java/)

###<a name="IDEs">Additional IDEs</a>###

* [Eclipse](http://www.eclipse.org/)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/)

###<a name="Help">Where to go for help</a>###

* **[Google] (http://www.google.com)** - Android Studio just came out of Beta in the fall, so if you need help with Android Studio specifically, make sure you check the dates of the search results and only use recommendations/answers from the last six months. Prior to this, Eclipse was a popular IDE choice, (and will probably remain widely used for the near future) so some tutorials may give you Eclipse directions.
* Come to **[Android Hack Nights](http://www.meetup.com/Women-Who-Code-DC/)**. You will get the most out of our hack nights if you follow one of our suggested resources.  These are the classes/books/resources that our members know the best and for which they can offer the most support.  The goal of the hack night is to help you learn the skills that will assist you with programming problems you may see in your workplace; not to actually assist you with work related to your job.  Asking problems specific to work projects derails the productivity of everyone at the event and may result in you not being included in future hack nights.

###<a name="Challenges">Challenges and Projects</a>###

Check out the **Challenges and Projects** document. [Coming soon].

###<a name="KeepInTouch">Keep in touch!</a>###
* [Tweet](https://twitter.com/WomenWhoCodeDC) us.
* Email us - WWCodeDC@gmail.com
* Check us out on [Github](https://github.com/womenwhocodedc).
* Visit our [website](http://womenwhocodedc.github.io/).
* Join our [Slack](https://docs.google.com/forms/d/1BXxIJuCawYt3pEzN7-6CgdT6XrhvG0KYQpOqdmv98DY/viewform) group.





