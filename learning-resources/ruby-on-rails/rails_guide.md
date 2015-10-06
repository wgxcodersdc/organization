# Women Who Code DC Ruby on Rails Guide

[Jump straight to the tools and resources](#tools)

##First Timers Section
**(But we won't judge if this helps others too)**

![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)

*If you are brand new to Ruby or Rails, we recommend coming to the first meeting of the month which is First-Timers Night.  You are welcome to come any week, but that first week will be the one we cater to beginners.*

###What is Ruby on Rails?
Ruby on Rails, (ROR) is an open source web application framework written in the Ruby language. Technically, it is a package library (specifically, a RubyGem) that is installed.

Rails establishes conventions for easier collaboration and maintenance. These conventions are codified as the Rails API (the application programming interface, or directives that control the code). The Rails API is documented [online](http://api.rubyonrails.org/) and described in books, articles, and blog posts. Learning Rails means learning how to use the Rails conventions and its API. Rails combines the Ruby programming language with HTML, CSS, and JavaScript to create a web application that runs on a web server. Because it runs on a web server, Rails is considered a server-side, or “back end,” web application development platform (the web browser is the “front end”).

Rails is more than a software library and an API. Rails is the central project of a vast community that produces software libraries that simplify the task of building complex websites. Members of the Rails community share many core values, often use the same tools, and support each other with an informal network that is built on volunteerism. Overlapping the informal community is an economic network that includes jobs, recruiters, consulting firms, conferences, businesses that build websites with Rails, and investors that fund startups. Rails is popular among web startups, significantly because the pool of open source software libraries (RubyGems, or “gems”) makes it possible to build complex sites quickly.

[source](http://railsapps.github.io/what-is-ruby-rails.html)

###What is Ruby?
Ruby is a programming language. It was created 20 years ago by Yukihiro “Matz” Matsumoto. By most measures of programming language popularity, Ruby ranks among the top ten, though usually as tenth (or so) in popularity, and largely due to the popularity of Rails. Like Java or the C language, Ruby is a general-purpose programming language, though it is best known for its use in web programming.

Ruby is known among programmers for a terse, uncluttered syntax that doesn’t require a lot of extra punctuation. Compared to Java, Ruby is streamlined, with less code required to create basic structures such as data fields.

Ruby’s key advantage is RubyGems, the package manager that makes it easy to create and share software libraries (gems) that extend Ruby. RubyGems provides a simple system to install gems. Anyone can upload a gem to the central [RubyGems website](https://rubygems.org/), making the gem immediately available for installation by anyone. The RubyGems website is where you’ll obtain the most recent version of Rails. And it is where you will obtain all the gems that help you build complex websites.

[source](http://railsapps.github.io/what-is-ruby-rails.html)

###What’s the difference between Ruby and Rails?

Remember that Rails is a web framework built using the Ruby language. Ruby is like the raw ingredients for a cake, the flour and sugar and so forth.  Rails is like the boxed cake mix.  It still has the same ingredients underneath, but it's packaged up to be quicker and easier to use.

*What’s a framework?*

A framework is a set of rules, conventions, tools to help you from reinventing the wheel. Frameworks make it so you don’t have to do common, tedious things that anyone making a website would have to do again. One of the core problems a website tries to solve is how to turn whatever the user requests (in the form of a URL) into code that accesses a database and returns something. Rails has developed a methodology and created an API that standardizes these interactions so you can focus on actually creating your app. 

*What’s MVC?*

The interactions between what a user sees on the webpage and what happens in the backend is complicated and can get very very large and intertwined. Rails uses an architecture called MVC to design the framework. MVC (model-view-controller) separates each part of that interaction into separate layers. It also help organize your code so that if any one new joins the project they know exactly where specific functions of the app will rest. MVC is pretty important to Rails and a lot of the intro courses will go over it but feel free to dive deeper into it. 

###What is Ruby on Rails used for? 

Twitter was initially built on Rails. It’s since moved off of the platform for scalability reasons. You’ll see a lot of Rails introductory classes use a Twitter-like application to explain the framework. Here are other sites that use ROR: 

1. Groupon
2. Bloomberg
3. Airbnb
4. SoundCloud
5. Square

[source](https://thecoderfactory.com/posts/top-15-sites-built-with-ruby-on-rails)

###Should I learn Ruby first or Rails first?
There are differing opinions on this but I like this approach from http://railsapps.github.io/what-is-ruby-rails.html: 

Do you need to study Ruby to learn Rails? The short answer is “no,” with one caveat. To avoid feeling overwhelmed when you first begin learning Rails, it is advisable to spend at least an hour with an introduction to Ruby so you are comfortable with the syntax of the language. You should be prepared to recognize correct formatting when you type Ruby code in your text editor. 

Be assured that you will indeed learn Ruby as you develop proficiency with Rails. Whether you study Ruby or not, you’ll develop Ruby skills as you learn Rails. Rails is largely a “domain specific language” that has its own set of directives distinct from the Ruby core. As you learn the Rails “language” you’ll be using the Ruby language syntax.
Your hardest challenge will be to learn the names of the structures you see in code examples. This is why it is helpful to work your way through a short introduction to Ruby. You’ll need to be able to recognize when you are looking at an array or a hash. You should recognize when you are looking at an iterator or the Ruby block syntax. Eventually, you’ll recognize more exotic Ruby formulations such as the lambda. It is okay if you can’t write a lambda function or even know when to use one; many Rails developers start work before learning Ruby thoroughly.

###How do I install Ruby?
If you use the link below to install Rails, it will also install a recent version of Ruby.

###How do I install Rails?
Rails used to be quite difficult to install but recent tools have made it a lot easier. On Macs you can use homebrew and RVM to install rails. Then install the Rails gem. On PCs railsinstaller makes it easy to install all the components. 

This website offers guidance on how to install Rails on Macs, PCs and Linux systems: http://installrails.com/

You can also use tools like Nitrious.io and c9.io to build Rails apps in a virtual machine. This doesn’t require you to install anything on your local machine. Most of the basic functionality is free from these websites but if you want to do more you can pay.

###What other tools do I need?
* Laptop: You can use a PC, Mac, or Linux.  There's an even mix of PC users and Mac users in this group who can share their perspectives, but if you're just starting out your operating system doesn't matter.
* Text Editor: We do not and should not code in regular word processors.  You need a user-friendly text editor that does syntax highlighting. These are some that we recommend:
  * [Sublime Text](http://www.sublimetext.com/) *Note: You can pay to stop seeing the occasional suggestion to buy it, but you do not have to.*
  * [TextWrangler](http://www.barebones.com/products/textwrangler/) - MAC only
  * [Notepad++](http://notepad-plus-plus.org/)
* Terminal/Console/Command Prompt(CMD)
		*It's a good idea to get comfortable using command prompt, most tutorials have an introductory lesson covering this. If you want more information covering this check out [Command Line Crash Course](http://learnpythonthehardway.org/book/appendixa.html)
*Git and GitHub: Version control is a really important part of any professional developer's toolkit. It helps with backing up your work, collaboration, and managing changes through iterative versions. You would need Git installed on your computer, and an account on [Github](https://github.com). For an introduction to Git and Github, refer to our [Intro to Git presentation](http://nupurkapoor.github.io/intro-to-git/#/)

###How do I run my ROR website? 
Rails comes with a built web server called WEBrick that you can run to test out your apps locally (cool!). When you are ready to deploy online there are several popular hosting services like Heroku that make it easy to run your app live. 

<a name="tools"></a>
##Suggested Learning Tools

You will get the most out of our meetups if you follow one of our suggested resources. These are the classes/books/resources that our members know the best and can offer the most support for.

We will not assist with work problems. We are here to help you learn the skills that will help you solve work problems, but asking about work related problems derails the productivity of everyone at the event. Repeated requests for solutions to work problems will result in our leaders asking you to leave.

####CS Beginner

If you want a great introdution to Computer Science and what programming is watch: [Harvard's CS50 Intro to CS class](https://courses.edx.org/courses/HarvardX/CS50x3/2015/info).  The first 3 weeks are essential but if you get into it...keep watching :) .

###Ruby Beginner

* [Try Ruby](http://tryruby.org/levels/1/challenges/0)
  * Short Interactive, Intro to the Ruby Programming Language
* [Code School](https://www.codeschool.com/paths/ruby)
  * Take the Ruby Language Path to get a deeper introduction to the language
* [Codecademy](http://www.codecademy.com/en/tracks/ruby)
  * An introduction to Ruby that runs from the basic all the way up through object-oriented programming.
* [Ruby Koans](http://rubykoans.com/) 
  * Testing based approach to learning Ruby (I really like this guide because it teaches you test based development).  Works best if you do not look to closely at the error messages because they give away the answer.
* [Learn Ruby the Hard Way](http://learnrubythehardway.org/book/)
  * Go through the exercises 
* [Ruby Algorithms](https://github.com/kdmcclin/ruby-algorithms)
  * This repository is a work in progress but contains a range of algorithms that you might find helpful.

###Rails Beginner
* [Rails for Zombies](https://www.codeschool.com/courses/rails-for-zombies-redux) 
  * a intro to the Ruby on Rails platform
* [Jumpstart Blogger](http://tutorials.jumpstartlab.com/projects/blogger.html)
  * Introductory Rails app tutorial, building a blog
* [Rails Tutorial](https://www.railstutorial.org/book)
  * a pretty in-depth but excellent intro to building an app in Rails
* [One Month Rails](http://onemonthrails.com/)
  * a more visual, interactive version of the guide above but it costs money
* [Codecademy](https://www.codecademy.com/courses/learn-rails)
  * In addition to Ruby Codecademy also has Rails app tutorials and tutorials on several APIs.
  
###Intermediate Projects

* [Codecademy](https://www.codecademy.com/apis)
  * In addition to Ruby and Rails tutorials, they also have several tutorials on working with various APIs
* [Build 12 apps in 12 weeks!](https://mackenziechild.me/12-in-12/) *Note: If using Devise with these, you will probably need to use the most recent version of the gem to avoid incompatability issues, not the version he specifies.*
* You can work on either of these projects together: 
  * https://github.com/LizAkins/TicTacToeSkeleton
  * https://github.com/WomenWhoCode/RubyTuesdays-ConnectFour

###Ruby/Rails Advanced
*Ready to contribute to larger projects?  Check out the following:*
* [Assembly](https://assembly.com/)
* [Contributing to Open Source](https://github.com/womenwhocodedc/organization/blob/master/learning-resources/awesome-coding-resources.md#open-source)

###Other Resources
* [Hacker Collective Resource List](https://github.com/HackerCollective/resources/blob/gh-pages/Programming/Web%20Development/Backend/RubyOnRails.md)
* [Facebook group for RoR](https://www.facebook.com/groups/HHRuby/)
* [RailsCasts](http://railscasts.com/)
  * These are great screencasts of tips, tricks, and tutorials. For pro episodes you have to subscribe but there are many great free ones.
* [Rails Documentation](http://guides.rubyonrails.org/)
