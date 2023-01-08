# NYCU_ML_Final_project
In this work, we are trying to solve a prediction problem, given a tabular data. The dataset itself is from the [kaggle contest](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview) that host in 2022 Aug. In the following section, I will go through the methodologies and summarize the cool idea that learned from the kaggle forum.

## How to train and inference ?

In this repostory, the train and the inference are seperated in the two files `0811514_train.ipybe` and `0811514_inference.ipynb`. Just simply open the notebook can click run-all then we can get the result. Note that, the training script will generate the model checkpoint (checkpoint.obj) that will be use at the inference stage, please make sure that you run the training code before you conduct the inference.


## Enviornment Information
+ python 3.9
  + numpy==1.20.3
  + pandas==1.3.4
  + matplotlib==3.4.3
  + colorama==0.4.4
  + scikit-learn==1.2.0
