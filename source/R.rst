Learning R
==========

.. _R:

.. Introduction

R is a more specific programming language compared to Python.
R is in essence a programming language aimed statistical programming. With R you can read data, manipulate data, do statistical analyses and visualize data.
In the course we will give you an introduction to all these components.

Preferably you will program R in the jupyter notebooks, but you are also allowed to use R Studio to program your notebooks. R Studio notebooks are very similar to jupyter notebooks. Instructions about the installation of R studio can be downloaded :download:`here <install_R_studio.html>`


A few remarks:

1.  We would advise you to make a directory structure with
    a. A folder called "Code", in which you save the notebooks
    b. A folder called "Output" in which you can save output like figures, tables etc.
    c. A folder called "Sourcedata" in which you save the data needed to run the notebooks
    In notebooks used in the course we assume you have implemented this directory structure.
2.  If you need to install a package you can run the following command in your jupyter notebook:
    install.packages('name_package', repos='http://cran.us.r-project.org')
3.  If you work on `<https://russet.uvt.nl/>`_ the directory structure and packages are pre installed.



Datacamp
--------

Most of R you learn yourself using datacamp. Follow the on-line videos and do
the on-line exercises. If you have questions about these, ask us during the
lecture or tutorial.

.. _week5:

Week 5
~~~~~~

What to do before class:
------------------------

* Datacamp: do the course `Introduction to R <https://www.datacamp.com/courses/free-introduction-to-r>`_

In class:
---------

In class we will work on different topics:

1.  Read data
    We will use :download:`this notebook <Readdata.ipynb>` for the jupyter notebooks (or :download:`this notebook <Readdata.Rmd>` for R Studio)
    And the 3 data files needed for this notebook:
    :download:`download 1<football.csv>`
    :download:`download 2<N1.csv>`
    :download:`download 3<football.xlsx>`
2.  Merging
    We will use :download:`this notebook <Merging.ipynb>` for the jupyter notebooks (or :download:`this notebook <merging.Rmd>` for R Studio)
    For this notebook, no data are needed
3.  For long to wide and vice versa
    We will use :download:`this notebook <Tidyr.ipynb>` for the jupyter notebooks (or :download:`this notebook <tidyr.Rmd>` for R Studio)
    And the data needed for this notebook:
    :download:`download <growth.csv>`

.. _week6:

Week 6
~~~~~~

What to do before class:
------------------------

* Datacamp: do the course `Data Visualization with ggplot2 (Part 1) <https://www.datacamp.com/courses/data-visualization-with-ggplot2-1>`_
* Assignment: :download:`this notebook <Graded_assignment1.ipynb>` for jupyter (or :download:`this notebook <graded_assignment_1.Rmd>` for R Studio)
  No data needed for this assignment

  * fill in the notebook
  * upload the notebook to github
  * add a link to this notebook in your README file on github

  * *Note*: this week's datacamp course are part of your pass/fail grade

  * *Note*: this week's assignment is part of your pass/fail grade

In class:
---------

In class we will work on different topics:

1.  A short recapitulation of ggplot2
    We will use :download:`this notebook <Recap_ggplot.ipynb>` for the jupyter notebooks (or :download:`this notebook <recap_ggplot.Rmd>` for R Studio)
    For this notebook, no data are needed
2.  Functions and Controls
    We will use :download:`this notebook <Functions_and_controls.ipynb>` for the jupyter notebooks (or :download:`this notebook <functions_and_controls.Rmd>` for R Studio)
    For this notebook, no data are needed
3.  Maps
    We will use :download:`this notebook <Maps.ipynb>` for the jupyter notebooks (or :download:`this notebook <maps.Rmd>` for R Studio)
    And the 4 data files needed for this notebook:
    :download:`download 1<nld_municipal_map.csv>`
    :download:`download 2<nld_municipal_data.csv>`
    :download:`download 3<nld_pc4_locations.csv>`
    :download:`download 4<hospital.csv>`
4.  Also :download:`download this zip-file <thematicmaps_2.1.tar.gz>`
	      

.. _week7:

Week 7
~~~~~~


What to do before class:
------------------------

* Datacamp: do the course `Data Manipulation in R with dplyr <https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial>`_
* Assignment: :download:`this notebook <Graded_assignment_2.ipynb>` for jupyter (or :download:`this notebook <graded_assignment_2.Rmd>` for R Studio)
  And the data needed for this notebook:
  :download:`download <graded_assignment_2.csv>`
  And you need to save this figure in the folder Sourcedata:
  :download:`download <barchart.png>`

  * fill in the notebook
  * upload the notebook to github
  * add a link to this notebook in your README file on github

  * *Note*: this week's datacamp course are part of your pass/fail grade

  * *Note*: this week's assignment is part of your pass/fail grade


In class:
---------

In class we will work on two topics:

1.  A very short recapitulation of dplyr
    We will use :download:`this notebook <Recap_dplyr.ipynb>` for the jupyter notebooks (or :download:`this notebook <recap_dplyr.Rmd>` for R Studio)
    For this notebook, no data are needed
2.  An introduction to linear regression
    We will use :download:`this notebook <Linear_regression.ipynb>` for the jupyter notebooks (or :download:`this notebook <linear_regression.Rmd>` for R Studio)
    And the data needed for this notebook:
    :download:`download <football.csv>`
