Github
======

We teach you to program in python and R and to explain your code using markdown.
For us (and others) to see what you have done, you should publish the jupyter
notebooks that you have worked on. For this course, we use github for you to
publish your results.

Further, as explained below, if you have questions about this course, you also
use github to ask these questions. Do not email us, as chances are that we
overlook your email.

Github is an extremely powerful tool as it allows for team collaboration and
version control in the cloud. Further, it allows you to publish webpages in
html. In fact, the documentation for this course is on github (as you can see in
the web address).

However, you do not need to know all this for the purpose of this course. We
will only use github for you to put your jupyter notebooks on line so that we
can grade them.



Sign up
-------

In order to use github, you need to sign up.

Go to the GitHub_ page and click on the green "sign up" button at the
top. At the join_ GitHub page, you set up a personal account. Fill in
the required information and click the green "Create an account"
button.

In step 2 choose the free account. Then move on to your dashboard
(step 3).

If you want, you can use your student status to get the `student developer pack
<https://education.github.com/pack>`_ which gives you --among other things--
some private repositories. Note that your assignments should be in a public
repository; otherwise we cannot grade them.

.. _questions:

questions
---------

If you have questions/comments about this course, go to the `issues
page <https://github.com/janboone/programming-for-economists/issues>`_
open a new issue (with the green "New issue" button) and type your
question. Use a title that is informative (e.g. not "question", but
"question about assignment 2"). Go to the next box ("Leave a comment")
and type your question. Then click on "Submit new issue". We will
answer your question as quickly as possible.

Information that we need to answer your question:

* say whether you are an ECO or EBE student
* mention the group number of your tutorial and/or the name of your tutorial teacher
* explain your question

The advantages of the issue page include:

* if you have a question, other students may have it as well; in this
  way we answer the questions in a way that everyone can see it. Also
  before asking the question, you may want to check whether it was
  asked/answered before on the issue page
* we answer your question more quickly than when you email us
* you increase your knowledge of github!

Only when you need to include privately sensitive information ("my cat
has passed away"), you can send an email.

In order to post issues, you need to create a github account (which
you need anyway to follow this course).

Note that if your question is related to another issue, you can react
to the earlier issue and leave a comment in that "conversation".


.. _posting:

Posting assignments on github
-----------------------------

Make a repository "assignments".

The following video explains how to create a repository, drag your jupyter
notebook onto github and add the link to your README file. To fill in the
webform, you only need to create a repository "assignments" as explained at the
start of the video.

`uploading your assignments with drag-and-drop using a browser <https://tilburgutube.uvt.nl/asset/detail/ZgVnJfSTQWPDobL3UDGgmB7m>`_

(depending on your media player, you may want to download the video first and then
watch it)

The web address of this repository "assignments" needs to be provided in the webform; go to :ref:`Important <important>`
for the address of the webform.

In the README file in the "assignments" repository you provide a link to each
assignment. Hence, after you have uploaded an assignment, adjust the README file
to include the web address of the jupyter notebook that you have just uploaded.

For the purpose of this course, it is enough if you can drag and drop files onto
your repositories. If you want a more sophisticated interaction with github,
look at the following section. But this is completely optional!

Optional
--------

If you want to use the command line to upload your assignments on github, you
need to set up Git on your computer (which you installed before) to work with
GitHub: this page explains how to set up Git_ for this purpose. Follow all the
steps described on this page. That is, both "Setting up Git" and "Next steps:
Authenticating with GitHub from Git". When it comes to "Authenticating with
GitHub from Git" follow the recommended route of "Connecting over HTTPS".

The following video shows how to clone a github repository to your computer,
using the command `git clone`, then we add a new assignment to the directory on
our computer and push it to github in the cloud:

`uploading your assignments using the shell or terminal  <https://tilburgutube.uvt.nl/asset/detail/u2Wa4MIbMrNegaOjJR042sYG>`_

The steps you take when using the shell are:

* only once, you need to clone the repository to your computer with `git clone`,
  in the video the command is `git clone https://github.com/janboone/assignments`
* then you change your directory at the command line into this new directory
  "assigmnents"; the command is `cd assignments`
* then you add a new jupyter notebook to your directory "assignments" or you
  change an existing notebook in this directory
* within this directory "assignments" type the following commands

  * `git add .`
  * `git commit -m "type some message that explains what you have
    added/changed"`
  * `git push`

* in case you changed your github repository from another computer and you want
  to synchronise the computer you are currently working, you do the following:

  * if your current computer does not have the repository yet, use `git clone`
    as above
  * if your current computer has the repository already but is "behind" what is
    on github, change into the directory "assignments" and type `git pull`. This
    brings your computer up-to-date with the github repository in the cloud.


.. _GitHub: https://github.com/
.. _join: https://github.com/join
.. _Git: https://help.github.com/articles/set-up-git/
.. _repository: https://help.github.com/articles/create-a-repo/
