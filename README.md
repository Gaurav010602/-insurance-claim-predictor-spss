# -insurance-claim-predictor-spss
Predicting insurance claims using IBM SPSS Modeler and CRISP-DM

This project aims to predict whether a policyholder is likely to make an insurance claim, using personal, health, and lifestyle-related attributes. The model assists insurance providers in identifying high-risk customers, enabling data-driven decisions for underwriting and risk management. The CRISP-DM (Cross-Industry Standard Process for Data Mining) framework was used to structure the analysis and ensure a robust data science workflow.

🔍 Objective :-
To build a classification model that predicts the likelihood of an insurance claim based on features such as age, gender, BMI, smoking status, physical activity, number of children, and region.

🧠 Methodology: CRISP-DM Framework
The project followed these six phases of CRISP-DM :-
1. Business Understanding - Predict insurance claims to support risk-based decision-making for insurers.
2. Data Understanding - Source: Public dataset from Kaggle
    Key Features:
    age, sex, bmi, steps, children, smoker, region, charges, insurance claim (target)
3. Data Preparation - Initial review and quality audit (100% accuracy)
    Variable role assignment: Continuous, Nominal, Flag
    Reclassification of categorical variables for correct interpretation
4. Modeling - Algorithm used: CHAID (Chi-squared Automatic Interaction Detection)
    Data split: 70% training, 30% testing
    Accuracy: 91.65%
5. Evaluation & Testing - Model evaluated on test set of 407 records
    Additional predictions performed on a hypothetical dataset (50 records)
    Post-processing done for readability of predictions
6. Deployment - Model saved and reused for batch predictions
    Results displayed in tabular format for easy interpretation

📊 Results :-
    Accuracy: 91.65%
    Model Type: Decision Tree (CHAID)
    Testing: Performed well on both real and hypothetical data

🧰 Tools & Technologies :-
     IBM SPSS Modeler
     CRISP-DM Methodology
     CHAID Algorithm
     Data Audit, Type, Reclassifier, Partition, and Analysis Nodes

✅ Conclusion
This project demonstrates a practical implementation of predictive modeling for insurance analytics. The CHAID model, with over 91% accuracy, shows strong potential  for deployment in real-world risk assessment systems.
