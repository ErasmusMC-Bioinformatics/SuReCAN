# MasterProjectAI_DariaKoppes

This Github page is for the reproducibility of the paper: **User-friendly machine learning Galaxy workflows for survival and treatment response prediction**

The code files contain the following information: 
  - *BenchmarkSVM_plus_preprocessing_datasets.ipynb*: Large file written in python where the titles throughout the file specify which training or test set is preprocessed. Preprocessing is done to get the inputs for the Galaxy workflows. Furthermore, datasets are processed to gather the input to make the Kaplan-meier plots shown in the paper.
  
    Note: Most of the code is taken from *test_model_prediction.ipynb* of the MODEL-P Github page with a few adjustments highlighted with comments. The preprocessing for the Kaplan-Meier plots and the datasets COMPASS and IKnowIT are new code. 
  - *Code_for_graphics.ipynb*: file written in R to make the Kaplan-meier plots and to make the nested cross-validation plots shown in the paper. 
