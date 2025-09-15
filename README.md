<h1>Predicting Airline Passenger Satisfaction with Neural Networks</h1>

<h2>Description</h2>
This project applied deep learning to the <i>Airline Passenger Satisfaction</i> dataset from Kaggle, aiming to predict passenger satisfaction levels based on personal attributes and flight experience factors. The solution was framed as a startup concept: a predictive service that empowers airlines to move from a reactive (survey-based) approach to a proactive strategy, improving customer experience, loyalty, and profitability.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>  
- <b>TensorFlow / Keras</b>  
- <b>Deep Neural Networks (DNN)</b>  
- <b>Scikit-learn</b>  


<h2>Methodology</h2>

1. <b>Data Exploration & Preprocessing</b>  
   - Dataset: Kaggle Airline Passenger Satisfaction dataset.  
   - Conducted data cleaning, missing value handling, and feature encoding.  
   - Split dataset into training, validation, and testing subsets.  

2. <b>Model Development</b>  
   - Designed a Dense Neural Network (DNN) using TensorFlow/Keras.  
   - Baseline comparison performed with logistic regression.  
   - Tuned hyperparameters (layers, neurons, activation functions, optimizers) to maximise predictive performance.  

3. <b>Model Training & Validation</b>  
   - Applied training with dropout layers and early stopping to reduce overfitting.  
   - Evaluated model with precision, recall, F1 score, and AUC metrics to align with business model requirements.  

4. <b>Business Model Context</b>  
   - Positioned as a predictive service for airlines, airports, and regulators.  
   - Revenue model designed around API subscriptions, contracts, and consulting.  
   - Marketing through aviation conferences, LinkedIn, and travel-tech partnerships.  

5. <b>Future Development</b>  
   - Identified the need for additional datasets (passenger feedback, operational data, profile data) to strengthen real-world deployment.  


<h2>Findings</h2>

- <b>Baseline Logistic Regression:</b> Accuracy ≈ 87.7%, F1 Score ≈ 0.877, AUC ≈ 0.873.  
- <b>Dense Neural Network:</b> Accuracy ≈ 96.4%, F1 Score ≈ 0.959, AUC ≈ 0.995.  
- Feature importance analysis highlighted key drivers such as in-flight service quality, baggage handling, and delays.  
- The DNN significantly outperformed traditional models, demonstrating the potential of deep learning to deliver actionable satisfaction predictions.  
- Business impact: enables airlines to predict dissatisfaction before it occurs, improve service delivery in real time, and reduce churn.  
