# BIP! Citation Classifier

The BIP! Citation Classifier is a comprehensive Python library designed to classify citations based on their intent, utilizing a range of state-of-the-art algorithms. 
This tool utilises the citation context found within scientific publications, analysing the text surrounding a reference to determine the intent (or purpose) behind the citation. 
By leveraging a well-established citation classification ontology, the library categorises citations into specific classes, such as whether a citation supports, uses, or extends the work being cited.
The outputs of the BIP! Citation Classifier are particularly useful for tasks such as citation network analysis, where understanding the nature of each citation can significantly improve the accuracy of various analyses. 

# Citation Classifiers in RPIs Calculation for Scientometrics

This project implements various text mining techniques based on neural networks, focusing on citation intent classification at different semantic levels. It also includes the modification and calculation of Relative Performance Indicators (RPIs) to observe how they are influenced by citation intent. All code is run on Google Colab.

# Project Structure
## Part I: Zero-Shot Classification Models
Six folders need to be created to store datasets, notebooks, and results of the Zero-Shot Classification Models.

1.Folder 1 – ACT:

Dataset: datasets/ACL_ATC/ATC/train.csv

Notebook: Inference_ZeroShotClassification/ZeroShotClassification_ACL_ATC_Classes6.ipynb

Contents: Inference results from four ZeroShotClassification models will be stored as .csv files. Model performance will be documented in the notebook.
