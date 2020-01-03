# ATLAS-UK-ML
ATLAS UK Machine Learning Tutorial notebooks, macros and scripts
-------------------------------------------------------------------------------------------------
This repo corresponds to jupyter notebooks, ROOT macros and scripts that have been created
in order to give concrete examples for people to use in order to start working with machine 
learning.  There are various technologies required in order to use this codebase, and this is
a considered choice

  - currently the predominant use of ML in particle physics is via the 
  home grown TMVA package in ROOT.  The BDT has become the ML algorihm of choice for the majority
  of particle physics analyses, and the default ROOT configuration uses ADAboost.M1.  So the slides
  (see below) describe that algorithm, link back to the original CS papers where the interested
  person can drill down into details of the algorithm. TMVA is a great package for getting started
  with machine learning in particle physics, especially as there is a really low threshold for
  accessing data (which for us would normally come from a root file).
  
  - Approximately half of hte PhD students in particle physics will leave the field to work in 
  industry, and most of the rest will move out into industry durign their postdoc career. Also
  times have changed and there are now widely accessible tools for doing machine learning. For
  these reasons we also have some Python API TensorFlow example scripts.  Some experiemnts are now
  starting to use Keras, TensorFlow and other framework toolkits that have been developed outside
  of the field of particle physics for machine learning - and by learning these you will pick up
  a transferable skill.

Please see the following web page for this material, which includes downloadable tar balls and 
slide deck pdf files:

  https://pprc.qmul.ac.uk/~bevan/teaching/ATLAS-UK-ML.html

Getting Started:
----------------
Clone the repository with the following command to get started with working with these examples.
     git clone --branch master https://github.com/adrianbevan/ATLAS-UK-ML.git

The examples pertaining to a given algorithm can be found in the different directories:

     BDT - decision trees using ROOT (C++)
     NN  - Neural Networks using TensorFlow (Python)


Software Requirements:
----------------------

ROOT can be installed from the CERN web page:
     https://root.cern.ch

The Python environment that these tutorials has been tested on is packaged in the Anaconda framework:
	   https://www.anaconda.com
  1. Install Anaconda
  2. Add the following packages:
        matplotlib
        scklearn
        tensorflow

-------------------------------------------------------------------------------------------------

If you are interested in machine learning then you may find some of my other machine 
learning tutorial examples online of interest. These can be found at the following page.
  https://pprc.qmul.ac.uk/~bevan/teaching.html

-------------------------------------------------------------------------------------------------
Author: Adrian Bevan (a.j.bevan@qmul.ac.uk)

Copyright (C) Queen Mary University of London

This code is distributed under the terms and conditions of the GNU Public License

-------------------------------------------------------------------------------------------------
