Installing the software
=======================


.. _install:

*Disclaimer*: below we describe the software that you need to
install for this course. Although we are not aware of any problems with these
programs, we cannot accept responsibility in case anything goes wrong
with your computer. Also, when you use this software, make sure
to save regularly and back up your work.

We need to install quite some software. This will be a bit of work and
things are bound to go wrong. So switch on some music_ and go ahead!

This is the first hurdle that you need to take to use open source
software. If you get an error message during installation, copy the
error message and google it. In 99 percent of the cases this will
solve your problem. If not; ask us in class.




Required installs for this course:
----------------------------------


* The first programming language that we use for this course is
  Python. We use the anaconda_ distribution. Make sure to install
  python 3.X.
* We will be using R from the Jupyter notebook. Open a "terminal" in
  Mac OS or "command prompt" (opdracht prompt) in Windows, type 'conda
  install -c r r-essentials' and press enter. More details can be
  found at `this
  page. <https://www.continuum.io/blog/developer/jupyter-and-conda-r>`_
  Note that you do not need to install R-studio for this (but you can; see below).

Check your installation
~~~~~~~~~~~~~~~~~~~~~~~
  
* to check whether your python install was successful, download and run :download:`this python notebook <python_test.ipynb>`
* to check whether your R install was successful, download and run :download:`this R notebook <R_test.ipynb>`
  

What if the installation does not work?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Most of the time, the instructions above work and you are done. What can you do if they do not work?

* ask us in class; we are usually able to solve your problems.
* work in the cloud: go to `<https://russet.uvt.nl/>`_ and log in
  with your TiU credentials. With this jupyter hub you can work both
  with R and python. This works perfectly fine, but there are two
  disadvantages. First, you cannot install packages yourself (but this
  is not necessary for the course). Second, you need an additional step to
  upload your notebooks and to get your notebooks on github.
* if you can work with python in the jupyter notebook but not with R, you can use R-studio. Instructions on how to install R-studio can be :download:`downloaded here. <install_R_studio.html>` 
  
Make sure that you have a working python and R environment before we
start using python in class. If you only figure out that R or python
is not working just before the deadline for an assignment, chances are
that you will fail...

  
Optional install
----------------

* We will be working with GitHub_ in this course. Most people will use
  the web-interface of github. In this case, you do not need to
  install anything. If you want to use the command line interface, you
  need to install Git_.

  * if you need more help here,
	`<http://git-scm.com/book/en/v2/Getting-Started-Installing-Git>`_
	may be useful and
	`<http://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup>`_.

If you want to work with github from the command line, you need a decent command
prompt/terminal/shell to work with. Note that this is optional as most operating
systems and browsers allow you to drag files onto github, which is simpler to
start with.

* Windows has a command-prompt_ installed by default. It is probably
  not the best terminal you can use. Here is a discussion of better
  consoles_ for windows. Note that the last link points to
  stackoverflow_; a website that you will be visiting a lot in the
  coming weeks!
* If you have a Mac, the application you need is called Terminal. But
  you may want to install iTerm2_, as it is more fancy and easier to
  work with.

If you have installed all this: congratulations, you are done! If you
experienced any problems, google to find a solution. If that does not work, ask us in class.


Working with the command line
-----------------------------

There are a number of situations where you may want to work with the command line (terminal, shell, command prompt, opdrachtprompt etc.):

* if you double click the icons of anaconda/jupyter, you may start up the notebook in the wrong directory (e.g. you cannot find the files of the course that you downloaded),
* you may want to use git from the command line,
* you are trying to type in 'conda install -c r r-essentials'

In each of these cases, it is useful to know some basic commands. We give some here:

* 'ls' (on Mac OS or linux) gives you an overview of the files in your current directory; on Windows the command is 'dir'
* if there is a directory called 'dir' that you would like to move to, type 'cd dir' where 'cd' stands for "change directory"
* if you want to move back to the directory above, type 'cd ..'
* if you want to make a new directory 'dir' type 'mkdir dir' where 'mkdir' stands for "make directory"
* in Windows: if you are on the 'C'-drive but would like to move to 'D', type 'D:'

.. _music: https://www.youtube.com/watch?v=6SFNW5F8K9Y
.. _Markdown: https://en.wikipedia.org/wiki/Markdown
.. _GitHub: https://github.com/
.. _Git: http://git-scm.com/downloads
.. _command-prompt: http://windows.microsoft.com/en-us/windows-vista/open-a-command-prompt-window
.. _consoles: http://stackoverflow.com/questions/60950/is-there-a-better-windows-console-window
.. _stackoverflow: http://stackoverflow.com/
.. _iTerm2: https://www.iterm2.com/
.. _python: https://www.python.org/
.. _ipython: http://ipython.org/
.. _anaconda: http://continuum.io/downloads
.. _quantitative: http://quant-econ.net/py/getting_started.html
