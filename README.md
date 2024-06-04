# Predicting Drug Safety in Pregnant Women Using Chemical Structure Analysis
Physiological changes during pregnancy affect drug pharmacokinetics and pharmacodynamics, making it difficult to assess the safety of medications for both mother and foetus. Traditional clinical trials are frequently limited or unavailable due to ethical constraints, resulting in gaps in our understanding of potential teratogenic dangers. However, artificial intelligence (AI) has emerged as a potent tool for evaluating vast, complicated information and categorizing medications based on chemical structures and multimodal properties. To forecast safety, an AI-based system can take into account pharmacological features, molecular structure, and clinical data.

Traditional medication safety review procedures, such as clinical trials and post-market surveillance, require a significant number of resources and time. Furthermore, pregnant women are frequently omitted from clinical studies, leaving a dearth of clear information for the safety of many medications in this demographic. This gap needs novel techniques to predicting the safety of drugs for pregnant women.

Advances in computational chemistry and machine learning provide potential approaches to addressing this difficulty. Researchers can construct predictive models for medication safety by using chemical descriptors, which are quantitative representations of molecular features. These models can evaluate massive databases of chemical substances, discover trends, and accurately anticipate probable detrimental effects.

## **Model Selection**

A Random Forest Classifier is chosen for its ability to handle complex data and provide robust performance in classification tasks. Given the nature of our data and the necessity for exact predictions, we are considering models like Random Forests. These models are reliable and capable of dealing with complex, high-dimensional data. Random Forests are especially useful for interpreting and handling unbalanced data.

Implementing and assessing the RandomForestClassifier on the dataset of drugs for pregnant women, the model achieved a 91% accuracy. This high accuracy implies that the chemical descriptors used are useful at distinguishing between safe and harmful drugs for pregnant women. The detailed evaluation metrics are listed below:

## **Test Set Performance:**

- Accuracy: 91%
- ROC AUC Score: 0.9594
- Kappa Score: 0.82
- MCC: 0.8217


## **Tools and Software Used**

- Pandas: Utilized for data manipulation and preprocessing tasks.
- Scikit-learn: Employed for model selection, evaluation, and hyperparameter tuning.
- Imbalanced-learn: Utilized to address class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).
- RDKit: Used for SMILES standardization and molecular descriptor calculation
