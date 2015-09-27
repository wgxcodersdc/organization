# Python for Programmers


## Package management

### pip
The go-to package manager for python is [`pip`](https://pip.pypa.io/en/latest/installing.html).

### virtualenv
A python virtual environment contains a python executable and `pip`. When activated, your `$PATH` is modified to point to the virtualenv's version of python and pip, and any pip-installed packages.

* To install, just run `pip install virtualenv`
* Make a new virtualenv named env by running `virtualenv env`. This will create a new directory `env` in your current directory, which houses all of the virtualenv things, including installed packages
* To activate, install, deactivate:
```
$ source env/bin/activate
(env) $ pip install pep8
Collecting pep8
  Downloading pep8-1.6.2-py2.py3-none-any.whl (40kB)
    100% |################################| 40kB 396kB/s
Installing collected packages: pep8

Successfully installed pep8-1.6.2
(env) $ deactivate
$
```

### virtualenvwrapper
virtualenv is great, but the invocation is kind of clunky. I recommend also installing [virtualenvwrapper](https://virtualenvwrapper.readthedocs.org/en/latest/) (`pip install virtualenvwrapper`), which provides some useful convenience commands. When you make virtualenvs with virtualenvwrapper, they get stored in `~/.virtualenvs`, which is set as `$WORKON_HOME`

* Create new virtualenvs with `mkvirtualenv <env name>`
* Deactivate with `deactivate`, as before
* Activate with `workon <env name>`, even if you have another virtualenv activated
* Delete a virtualenv with `rmvirtualenv <env name>`

There's also lots of hooks and things to further customize your environment.

## The Zen of Python
The python community is pretty serious about programming conventions and striving to embody the Zen of Python. Pythonistas believe that standard styling and formatting make it easier to read someone else's code. If you want the full details, go read the [pep8 standard](https://www.python.org/dev/peps/pep-0008/). Or just install a pep8 linter and change your editor to 4-space indentation.

```
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

## Learning Resources

* [Official Python Tutorial](https://docs.python.org/2/tutorial/index.html) :books:
* [Dive Into Python](http://www.diveintopython.net/) :books: for impatient programmers
* [Core Python Programming](http://www.amazon.com/dp/0132269937/) :books: :moneybag: $28 kindle, $39 paperback, for those who want a more comprehensive experience
* [Crash Into Python](http://stephensugden.com/crash_into_python/) :books:
* [Python Antipatterns](http://lignos.org/py_antipatterns/) :page_facing_up: A short guide to avoiding anti-Pythonic patterns frequently used by programmers coming from other languages.

### Learning Resources Legend
* :computer: - interactive courses or labs
* :pencil: - problem sets or independent coding exercises
* :school_satchel: - fully-featured courses or classes
* :video_camera: - videos
* :headphones: - podcasts
* :books: - books or long reads
* :page_facing_up: - articles or short reads
* :beginner: - tutorial style, guided
* :moneybag: - paid resource
* :wrench: - development tools
