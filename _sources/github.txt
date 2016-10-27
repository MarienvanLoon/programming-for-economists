Github
======

We teach you to program in python and R and to explain your code using markdown. For us (and others) to see what you have done, you should publish the jupyter notebooks that you have worked on. For this course, we use github for you to publish your results.

Github is an extremely powerful tool as it allows for team collaboration and version control in the cloud. Further, it allows you to publish webpages in html. In fact, the documentation for this course is on github (as you can see in the html address).

However, you do not need to know all this for the purpose of this course. We will only use github for you to put your jupyter notebooks on line so that we can grade them.



Sign up
-------

In order to use github, you need to sign up.

Go to the GitHub_ page and click on the green "sign up" button at the
top. At the join_ GitHub page, you set up a personal account. Fill in
the required information and click the green "Create an account"
button.

In step 2 choose the free account. Then move on to your dashboard
(step 3).

If you want, you can use your student status to get the `student developer pack <https://education.github.com/pack>`_ which gives you --among other things-- some private repositories. Note that if you make assignments in a private repository, you need to share it with us; otherwise we cannot grade your assignments.

set up Git
----------

Next, we need to set up Git on your computer (which you installed
before) to work with GitHub: this page explains how to set up Git_ for
this purpose. Follow all the steps described on this page. That is,
both "Setting up Git" and "Next steps: Authenticating with GitHub from
Git". 

When it comes to "Authenticating with GitHub from Git" follow the recommended route of "Connecting over HTTPS". 


repository
----------

???adjust below; no gh-pages; everything with first-repo???


.. note::

   GitHub has changed the style of its webpages since the screenshots below were made; hence what you will see is not identical but it will be close enough for you to understand what you should be doing


* Now create your first repository_. Call this, for instance, "first-repo":

.. image:: /images/github_repo_1.png
   :scale: 90 %
   :align: center
		   
* Click on "Create repository", and then you see (but not the arrow...):

		   
.. image:: /images/github_repo_2.png
   :scale: 90 %
   :align: center


* Using Windows Explorer on Windows (Finder on Mac) or whatever
  program you like, create a new directory "github" in a place that
  you can navigate to using the command line. On Windows, you may want
  to create it as "C:\\github"; on Mac as "~/github".


On Linux and Mac computers, "~" indicates your home-directory. On most terminals you can use the "tab" key to complete what you are typing. Hence typing "~/git 'tab'" will complete to "~/github"; unless you have a directory "~/gitty" in which case the terminal will ask you which completion you want. Similarly for "C:\\git" on Windows.

  
* Go to your command line (e.g. command prompt under Windows or
  another console; Terminal or iTerm2 under Mac, whatever you
  installed :ref:`here <install>`).

* Navigate to the new directory "github" by typing at the command line
  either :command:`cd C:\\github` or :command:`cd ~/github` (whatever directory you chose
  to create)

* Type at the command line: :command:`git clone
  https://github.com/janboone/second-repo` where you change
  "/janboone/second-repo" to your own user name (instead of
  "janboone") and the name of the repository just created (if you did
  not choose "second-repo")

* The terminal will give output like

::
  
  Cloning into 'second-repo'...
  remote: Counting objects: 3, done.
  remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
  Unpacking objects: 100% (3/3), done.
  Checking connectivity... done.  

* Note that at this point there is no need to understand what you are
  typing here and why. This will become clear later

* Type: :command:`cd second-repo`

* :command:`git checkout --orphan gh-pages`

::

  Switched to a new branch 'gh-pages'

* :command:`git rm -rf .` --note that this is "-rf [space] ."

::

  rm 'README.md'
   
* :command:`touch .nojekyll` --this is step is (only) necessary if you want to
  use sphinx; clearly, the step should be skipped if you do want to use Jekyll.

.. _buttondown:
  
* Download the following two files and copy them to your directory
  "github/second-repo". That is, "C:\\github\\second-repo" on Windows if
  you followed the instructions above or "~/github/second-repo" on
  Mac. These are the two files from `<https://github.com/ryangray/buttondown>`_:

    * :download:`the markdown file <pandoc_example.md>`
    * :download:`the css style file <buttondown.css>`

* Use pandoc to covert the markdown file "pandoc_example.md" into an
  html file (here "index.html") using the style information from
  "buttondown.css"
	   
    * :command:`pandoc pandoc_example.md -s -c buttondown.css -o index.html`
	  
* To see what a css file does for html, we also convert to html
  without the css file:
	  
    * :command:`pandoc pandoc_example.md -o NoCss.html`

* :command:`git add .`

* :command:`git commit -a -m "First pages commit"`

::
	 
   [gh-pages (root-commit) 8d3b1d1] First pages commit
   5 files changed, 1154 insertions(+)
   create mode 100644 .nojekyll
   create mode 100644 NoCss.html
   create mode 100755 buttondown.css
   create mode 100644 index.html
   create mode 100755 pandoc_example.md
  
* :command:`git push origin gh-pages`

::

  Counting objects: 7, done.
  Delta compression using up to 8 threads.
  Compressing objects: 100% (6/6), done.
  Writing objects: 100% (7/7), 8.45 KiB | 0 bytes/s, done.
  Total 7 (delta 2), reused 0 (delta 0)
  To https://github.com/janboone/second-repo
  [new branch]      gh-pages -> gh-pages


* Go to the website: "http://janboone.github.io/second-repo/" where
  you change "janboone" into your own github user name and
  "second-repo" into the name of your own second repository. Note that it may take some time before your changes are published on line.





assignments
-----------


Make a repository "assignments".

The address of this repository in webform at ???

Webform asks for:

* github account name
* html address of your repository "programming_assignments"
* DataCamp account name
* your ANR
* your uvt-email address

  
The readme file in the "programming_assignments" repository contains a link to each assignment. Hence, after you have uploaded an assignment, adjust the readme file to include the html address of the jupyter notebook that you have just uploaded.




???add text; explain???


depending on your media player, you may want to download the videos and then watch them

`uploading your assignments with drag-and-drop using a browser <https://tilburgutube.uvt.nl/asset/detail/ZgVnJfSTQWPDobL3UDGgmB7m>`_




`uploading your assignments using the shell or terminal  <https://tilburgutube.uvt.nl/asset/detail/u2Wa4MIbMrNegaOjJR042sYG>`_

Detailing the steps when using the shell:


questions
---------

As explained ?here? you also use github if you have questions about the course.

