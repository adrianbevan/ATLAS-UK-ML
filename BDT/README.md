# ATLAS-UK-ML / BDTs
ATLAS UK Machine Learning Tutorial - Boosted Decision Trees
-------------------------------------------------------------------------------------------------
This folder contains TMVA-based macros that can be used to train different boosted decision trees,
and to compare the reciever operating characteristic (ROC) curve performance between different models.
The following macros exist:

  - TMVAClassification.C : Basic TMVA macro that will use the standard TMVA example data to 
    learn how to distinguish between a signal and background class.  This macro is setup to 
    train a BDT using the AdaM1 boost algorithm.  The following hyper parameters are set for 
    the default example:
      NTrees                  = 850
      Min node size           = 2.5%
      Max depth of a tree     = 3
      Boost type              = AdaBoost
      Ada boost beta          = 0.5
      UseBaggedBoost          = flag set
      Bagged sample fraction  = 0.5
      Separation type         = Gini index
      nCuts                   = 20
    Please see the TMVA user guide for an explanation of the configuration parameters:
       https://root.cern.ch/download/doc/tmva/TMVAUsersGuide.pdf 
    
  - TMVAClassificationApplication.C : Basic TMVA example for reading in data and processing it
    such that a new trained MVA s computed, using hte TMVA::Reader.
  
  - Compare.C : Compare the four MVA examples that you will train in the tutorial.  The output of this
    macro is Compare.pdf, which shows the 4 ROC curves for the four trained BDTs from this example.
    
  - Htautau.C : An example of the TMVA training macro that has been adapted to use the Kaggle Higgs to 
    tautau data as an input.
    
The aim of these macros is to introduce you to how to use TMVA to train a BDT, and to get you to start thinking
about some of the training options for the BDT algorithm.  This is arguably the most common machine learning
algorithm used in particle physics today, and so the tutorial is considered as an entry to this topic, that you
may wish to build upon.

Please see the following web page for this material, which includes downloadable tar balls and
slide deck pdf files:

  https://pprc.qmul.ac.uk/~bevan/teaching/ATLAS-UK-ML.html

-------------------------------------------------------------------------------------------------

If you are interested in machine learning then you may find some of my other machine
learning tutorial examples online of interest. These can be found at the following page.
  https://pprc.qmul.ac.uk/~bevan/teaching.html

-------------------------------------------------------------------------------------------------
Author: Adrian Bevan (a.j.bevan@qmul.ac.uk)

Copyright (C) Queen Mary University of London

This code is distributed under the terms and conditions of the GNU Public License

-------------------------------------------------------------------------------------------------
