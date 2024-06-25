# PCfinalproject
Pablo Cuadros Final Project (INFO H515)
# Predictive Modeling for Diabetes Using CDC Health Indicators Data

## Abstract/Overview
This project aims to develop a predictive model for diabetes using the CDC Diabetes Health Indicators dataset. The primary purpose of this project is to provide a reliable tool for early diabetes detection, leveraging demographic and medical history features. This model can be integrated into healthcare systems to assist medical professionals in identifying individuals at risk of diabetes, enabling timely intervention and management. Stakeholders such as healthcare providers, policymakers, and public health officials would benefit from this tool by gaining insights into diabetes risk factors, improving patient outcomes, and devising effective public health strategies.

## Data Description
The dataset used in this project is the CDC Diabetes Health Indicators dataset, which contains various health-related features for individuals, including demographic information and medical history. The dataset includes the following features:

- **Demographic Information**: Age, Sex, Education, Income
- **Medical History**: HighBP, HighChol, CholCheck, BMI, Smoker, Stroke, HeartDiseaseorAttack, PhysActivity, Fruits, Veggies, HvyAlcoholConsump, AnyHealthcare, NoDocbcCost, GenHlth, MentHlth, PhysHlth, DiffWalk

The target variable is `Diabetes_binary`, indicating whether an individual has diabetes or not.

## Algorithm Description
The project employs a logistic regression algorithm to predict diabetes based on the selected subset of features (demographic and medical history). Logistic regression is chosen for its simplicity, interpretability, and strong baseline performance in preliminary evaluations. The algorithm works by estimating the probability that a given input point belongs to a certain class (in this case, diabetic or non-diabetic) and is particularly suited for binary classification tasks.

## Tools Used
- **Python**: The primary programming language used for data manipulation, model training, and evaluation.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For implementing logistic regression, splitting data, and evaluating model performance.
- **Joblib**: For saving and loading the trained model.

## Ethical Concerns
Several ethical and societal implications must be considered for this application:
- **Data Privacy and Security**: The data used contains sensitive health information. Ensuring that the data is anonymized and securely stored is crucial to protect individual privacy.
- **Bias and Fairness**: The model should be evaluated for any biases that may exist due to the demographic or health-related features used. It is essential to ensure that the model does not disproportionately affect any particular group.
- **Transparency and Interpretability**: Given the healthcare context, it is vital that the model's predictions are interpretable and transparent. Healthcare providers need to understand how predictions are made to trust and act on them.
- **Informed Consent**: Individuals whose data is used should be informed about how their data will be used and should consent to its usage.
- **Risk of Misuse**: There is a risk that the model could be misused if deployed without proper validation and oversight. Ensuring that the model is used as an assistive tool rather than a definitive diagnostic tool is crucial to mitigate this risk.

In conclusion, by addressing these ethical concerns and ensuring the model is used responsibly, the predictive tool can significantly contribute to early diabetes detection and better health outcomes.
