# NLP-CW
Paul Caprariu (apc4818), Maxim Fishman (maf221), Clarence Ng (cn21)

This notebook contains the code for exploratory data analysis, model training, and results analysis for the approaches that we used. 

The notebook is written to be run in Google Colab. 

It is organised as follows: 
1. **Imports and Data Loading**: We install and load key libraries, and load the PCL dataset. 
2. **Exploratory Analysis**: We explore the datasets.
3. **RoBERTa Baseline**: We reproduce the RoBERTa baseline provided by the contest organisers.
4. **Data Augmentation and Prep**: Functions for preparing the dataset for model training, including data augmentation via synonym replacement, dataset balancing, and preparing the validation set for hyperparameter tuning. 
5. **Hyperparameter Search**: Explores different model configurations and hyperparameters to find the best performing option. 
6. **Final Model**: We take the best performing configuration from the hyperparameter search and retrain the model with the entire training set. 
7. **Results Analysis**: We analyse the results of the final model in further detail. 
8. **Codalab Submission**: Code to generate outputs for the Codalab test set. 
9. **Alternative Approach Explored: Textual Entailment**: An alternate approach that we explored using textual entailment for feature construction. Unfortunately this did not prouce viable results
