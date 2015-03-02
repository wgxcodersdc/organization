#A Guide for First Timers
###(But we won't judge if this helps others too)

![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)![Ruby On Rails Icon](http://files.softicons.com/download/application-icons/ruby-programming-icons-by-ahmad-galal/png/48/RubyOnRails.png)

*If you are brand new to Ruby or Rails, we recommend coming to the first meeting of the month which is First-Timers Night.  You are welcome to come any week, but that first week will be the one we cater to beginners.*

##What is Ruby on Rails?
Ruby on Rails, (ROR) is an open source web application framework written in the Ruby language. Technically, it is a package library (specifically, a RubyGem) that is installed.

Rails establishes conventions for easier collaboration and maintenance. These conventions are codified as the Rails API (the application programming interface, or directives that control the code). The Rails API is documented [online](http://api.rubyonrails.org/) and described in books, articles, and blog posts. Learning Rails means learning how to use the Rails conventions and its API. Rails combines the Ruby programming language with HTML, CSS, and JavaScript to create a web application that runs on a web server. Because it runs on a web server, Rails is considered a server-side, or “back end,” web application development platform (the web browser is the “front end”).

Rails is more than a software library and an API. Rails is the central project of a vast community that produces software libraries that simplify the task of building complex websites. Members of the Rails community share many core values, often use the same tools, and support each other with an informal network that is built on volunteerism. Overlapping the informal community is an economic network that includes jobs, recruiters, consulting firms, conferences, businesses that build websites with Rails, and investors that fund startups. Rails is popular among web startups, significantly because the pool of open source software libraries (RubyGems, or “gems”) makes it possible to build complex sites quickly.

(from: http://railsapps.github.io/what-is-ruby-rails.html)

##What is Ruby?
Ruby is a programming language. It was created 20 years ago by Yukihiro “Matz” Matsumoto. By most measures of programming language popularity, Ruby ranks among the top ten, though usually as tenth (or so) in popularity, and largely due to the popularity of Rails. Like Java or the C language, Ruby is a general-purpose programming language, though it is best known for its use in web programming.

Ruby is known among programmers for a terse, uncluttered syntax that doesn’t require a lot of extra punctuation. Compared to Java, Ruby is streamlined, with less code required to create basic structures such as data fields.

Ruby’s key advantage is RubyGems, the package manager that makes it easy to create and share software libraries (gems) that extend Ruby. RubyGems provides a simple system to install gems. Anyone can upload a gem to the central [RubyGems website](https://rubygems.org/), making the gem immediately available for installation by anyone. The RubyGems website is where you’ll obtain the most recent version of Rails. And it is where you will obtain all the gems that help you build complex websites.

(from: http://railsapps.github.io/what-is-ruby-rails.html - read about the disadvantages as well)

##What’s the difference between Ruby and Rails?

Remember that Rails is a web framework built using the Ruby language. 

What’s a framework?

A framework is a set of rules, conventions, tools to help you from reinventing the wheel. Frameworks make it so you don’t have to do common, tedious things that anyone making a website would have to do again. One of the core problems a website tries to solve is how to turn whatever the user requests (in the form of a URL) into code that accesses a database and returns something. Rails has developed a methodology and created an API that standardizes these interactions so you can focus on actually creating your app. 

What’s MVC?

The interactions between what a user sees on the webpage and what happens in the backend is complicated and can get very very large and intertwined. Rails uses an architecture called MVC to design the framework. MVC (model-view-controller) separates each part of that interaction into separate layers. It also help organize your code so that if any one new joins the project they know exactly where specific functions of the app will rest. MVC is pretty important to Rails and a lot of the intro courses will go over it but feel free to dive deeper into it. 

##What is Ruby on Rails used for? 

Twitter was initially built on Rails. It’s since moved off of the platform for scalability reasons. You’ll see a lot of Rails introductory classes use a Twitter-like application to explain the framework. Here are other sites that use ROR: 

1. Groupon
2. Bloomberg
3. Airbnb
4. SoundCloud
5. Square

(https://thecoderfactory.com/posts/top-15-sites-built-with-ruby-on-rails)

##Should I learn Ruby first or Rails first?
There are differing opinions on this but I like this approach from http://railsapps.github.io/what-is-ruby-rails.html: 

Do you need to study Ruby to learn Rails? The short answer is “no,” with one caveat. To avoid feeling overwhelmed when you first begin learning Rails, it is advisable to spend at least an hour with an introduction to Ruby so you are comfortable with the syntax of the language. You should be prepared to recognize correct formatting when you type Ruby code in your text editor. 

Be assured that you will indeed learn Ruby as you develop proficiency with Rails. Whether you study Ruby or not, you’ll develop Ruby skills as you learn Rails. Rails is largely a “domain specific language” that has its own set of directives distinct from the Ruby core. As you learn the Rails “language” you’ll be using the Ruby language syntax.
Your hardest challenge will be to learn the names of the structures you see in code examples. This is why it is helpful to work your way through a short introduction to Ruby. You’ll need to be able to recognize when you are looking at an array or a hash. You should recognize when you are looking at an iterator or the Ruby block syntax. Eventually, you’ll recognize more exotic Ruby formulations such as the lambda. It is okay if you can’t write a lambda function or even know when to use one; many Rails developers start work before learning Ruby thoroughly.

##How do I install Ruby?

##How do I install Rails?
Rails used to be quite difficult to install but recent tools have made it a lot easier. On Macs you can use homebrew and RVM to install rails. Then install the Rails gem. On PCs railsinstaller makes it easy to install all the components. 

This website offers guidance on how to install Rails on Macs, PCs and Linux systems: http://installrails.com/

You can also use tools like Nitrious.io and c9.io to build Rails apps in a virtual machine. This doesn’t require you to install anything on your local machine. Most of the basic functionality is free from these websites but if you want to do more you can pay.

##How do I run my ROR website? 
Rails comes with a built web server called WEBrick that you can run to test out your apps locally (cool!). When you are ready to deploy online there are several popular hosting services like Heroku that make it easy to run your app live. 

##What’s the best way to learn Ruby?
If your goal is to jump right into Rails you can follow the advice above and get an introduction to Ruby with:

* tryruby.org
* rubymonk.com

For more advanced Ruby 
* resources coming soon

##What’s the best way to learn Rails?

##How do I find projects that I can help out with? 
