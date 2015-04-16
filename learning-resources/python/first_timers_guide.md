# WWCDC Python Study Group first timer's guide

If you are brand new to Python, we recommend coming to the first meeting of the month which is First-Timers Night. You are welcome to come any week, but that first Thursday will always cater to beginners.

## What is Python?
Python is a powerful and approachable programming language. It has an easy-to-learn syntax, which makes it an excellent language for beginners. Out of the box, Python is a powerful scripting language. It can be used to write all kinds of programs, from a simple tip-calculator to a fully-featured command-line Twitter client, or a program that automatically corrects your code for style consistency.

Additionally, the Python community provides a variety of tools for common applications. For web development, [Django](https://www.djangoproject.com/) is a fully-featured web framework, similar to Ruby on Rails. It powers a lot of popular websites, including Pinterest and Instagram. There are also lightweight web framework options, like [Flask](http://flask.pocoo.org/).

Python is a big player in the science and data communities. The [scipy](http://www.scipy.org/) family of libraries support a variety of science, math, and engineering applications, and [scikit-learn](http://scikit-learn.org/stable/) is a popular Python library for machine learning. The [natural language toolkit (nltk)](http://www.nltk.org/) is one of the best tools anywhere for parsing and analyzing natural human language. Python is a perfectly suitable language for writing code in the [Hadoop Ecosystem](http://blog.cloudera.com/blog/2013/01/a-guide-to-python-frameworks-for-hadoop/), with packages like [MRJob](https://pythonhosted.org/mrjob/) (Map Reduce Job) and [Apache Spark](https://spark.apache.org/).

Python is also the main user-programming language for the [raspberry pi](http://www.raspberrypi.org/).

## Which tools do I need?
You can write and run Python programs on PCs, Macs, and Linux machines, so long as you have a Python interpreter installed. (On Mac and most Linux distributions, Python comes installed out-of-the-box.) See below for installation instructions on Windows.

You will also need a program to edit your code. While there are Interactive Development Environments (IDEs) for Python, we recommend starting with a regular text editor. [SublimeText](http://www.sublimetext.com/) is a popular and powerful text editor that is available on all OSs. [Notepad++](http://notepad-plus-plus.org/) is also a nice option for Windows. We strongly recommend that you do not use a bare-bones text editor like Notepad on Windows or TextEdit on Mac for editing your code. These programs lack syntax-highlighting and have no support for plugins that can help you learn faster and be more productive.

## Installing Python
1. Open up a Command Prompt window.
    * Windows: Start > Search > type in "`cmd`" > push 'Enter'
    * Mac: `Apple Button` + `Space` > type in "`terminal`" > push Enter
    * Ubuntu 14.04: `Ctrl` + `Alt` + `t`
1. In the command prompt, type `python` and push Enter.
    * If a different prompt shows up, congratulations! You already have Python installed.
    * If you got an error, follow the instructions below to install Python. It might look complicated, but [this video shows that it can be done easily in under 3 minutes](https://www.youtube.com/watch?v=dU_ca27EGT8):
1. If the `python` command gave you got an error, navigate your web browser to [the Python downloads page](https://www.python.org/downloads/) and download the *Python 2.7* file for your operating system.
1. Install Python to the default location (assuming you're running Windows, `C:\Python27`)
1. When the installation is complete, on your computer navigate: `My Computer > [System] Properties > Advanced [System Settings] > Environment Variables`
1. Under `System Variables` scroll down until you find the _Variable_ called `path`. Push the `edit` button and add `;C:\Python27;` to the end of the `variable value` field.
    * Note: This list is semicolon-separated. It will look like: `a;b;c;d;`, and you are just adding another item. There shouldn't be two semicolons next to each other.
1. Exit out of all Command Prompt windows, open a new one (`Start > Search > "cmd" > Enter`), type `python` then push Enter.
1. That's it! You've gotten over the worst part!

### A note on Python versions
Python 3 introduced a lot of breaking changes, so even though it's been around for a decade, many people still use Python 2. There are still some [popular libraries](http://py3readiness.org/) that don't support Python 3, but the vast majority do. So, for most purposes, it doesn't matter which version you use, but Python 2.7 is probably the safest.


## Study Materials

### Learning Resources Legend
* :computer: - interactive courses, labs, or problems
* :video_camera: - videos
* :headphones: - podcasts
* :books: - books or long reads
* :page_facing_up: - articles, short reads, or tutorials
* :moneybag: - paid resource


### Courses
* [MIT 6.00SC: Introduction to Computer Science and Programming](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/) -- :video_camera: , problem sets

### Books
* [Guttag, Introduction to Computer Science and Programming with Python](http://www.amazon.com/gp/product/0262525003/) -- :moneybag: $15 kindle, $20 paperback
* [ThinkPython](http://en.wikibooks.org/wiki/Think_Python/Preface) -- Free
* [Test-Driven Development with Python](http://chimera.labs.oreilly.com/books/1234000000754) -- Free online!

### Tutorials
* [Learn Python the Hard Way](http://learnpythonthehardway.org/book/) -- :books: - Free
