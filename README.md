# LoLa-Decision-Tree-Paper
This repository contains the code required to repeat our expriments using the Decision tree and Random forest classifiers to predict the entailment relations on the SNLI data. We provide the code to create the features we used for this problem.

The create_data notebook is responsible for reading the snli data and creating the additional features to be used for the NLI classification task. 
The train_eval notebook contains the code we used to train our Decision tree and Random forest classifiers and evaluation (calculation of performance metrics).
The final csv files were too large to be uploaded to github so we provide a zipped file with our data combined. However the code expects 3 csv files with the suffixes '_train', '_dev', and '_test'.

Aknowledgements: This code is based on the Tools Notebook for the Logic & Language course by Lasha.Abzianidze@gmail.com
