# Fracture-Stage-Classification
Classification of Fracture Stages in Oil &amp; Gas drilling operations

### Predicting and flagging hard to treat fracture stages prior to the fracture start date will eliminate surprises during the fracturing, the features that identifies a fracture being in stage 0 or stage 1 are as following:
1. Measured depth in feet
2. Resistivity in ohm-m
3. Youngs Modulus divided by Poissons ratio
4. Gamma ray
5. Minimum horizontal stress

### If a drilling operation is at stage 1, more chemicals are required to treat the stage, through out this project I have accomplished the following

* Analyzed and feature engineered the Dataset to make it ready to be fed to different Classification Models
* Built and Tuned Support Vector Machine, Random Forest, Extra Trees, Gradient Boosting and XGBoost Machine Learning models to Classify Fracture Stages in oil & gas drilling operations
* Determined the best performing model by running each model on 10-Fold cross validations and comparing the average F1-Score for each model.
* Achieved an F1-Score of 0.94 on the Support Vector Machine model (Best performing model)
