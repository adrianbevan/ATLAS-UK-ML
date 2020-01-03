# ATLAS-UK-ML / data
ATLAS UK Machine Learning Tutorial - Kaggle Higgs challenge data sample
-------------------------------------------------------------------------------------------------
This folder contains two small example training files for the Kaggle Higgs training set. These data
are provided to allow the user to get a feel for training machine learning algorithms using realistic
HEP data.  More details about the Kaggle Higgs data challenge can be found at:

    https://www.kaggle.com/c/higgs-boson

The files included are:
    
  - train_sml_bg.csv : 5000 training examples of the background type.

  - train_sml_sig.csv : 5000 training examples of the signal type.

Note that the number of training examples provided here is small, and that one should take care to 
understand if the learned models are over trained or not.  If you have a configuration that you would 
like to study in more detail then you should consider trianing using a more realistic larger training 
sample.  You can download those via the Kaggle web page, or alternatively pick these up from the 
following page:

	  https://pprc.qmul.ac.uk/~bevan/statistics/TF/data.zip

The aim of this example is to provide you with a realistic HEP problem. There are many different featres
that can be used to learn how to distinguish between the signal and background, and in addtion to the 
hyper parameters of your model; the content and dimensionality of the feature space you want to learn
from will affect how well your model can be learned, and how well it will perform.

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
