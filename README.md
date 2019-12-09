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


-------------------------------------------------------------------------------------------------

If you are interested in machine learning then you will find some of my other machine 
learning tutorial examples online at the following page.
  https://pprc.qmul.ac.uk/~bevan/teaching.html

-------------------------------------------------------------------------------------------------
Author: Adrian Bevan (a.j.bevan@qmul.ac.uk)
Copyright (C) Queen Mary University of London
This code is distributed under the terms and conditions of the GNU Public License

-------------------------------------------------------------------------------------------------
