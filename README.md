# fault_prediction01
 Problem Statement
Modern power distribution systems require rapid and accurate fault detection to maintain grid stability and prevent large-scale outages. Faults like line-to-ground, line-to-line, or three-phase faults can disrupt electricity supply and cause significant economic losses if not identified quickly.

The challenge is to design a machine learning model capable of detecting and classifying these faults using electrical measurement data (voltage & current phasors).

Dataset: Kaggle - Power System Faults Dataset
Proposed Solution
A machine learning-based fault detection system, developed and deployed on IBM Cloud Lite, that:

Analyzes voltage and current data

Classifies fault types (Line-to-Ground, Line-to-Line, Three-Phase)

Differentiates between normal and faulty operating conditions

Enables real-time fault detection for improving grid reliability
Technologies Used
IBM Watsonx.ai Studio (Model development & deployment)

IBM Cloud Lite (Cloud platform)

IBM Cloud Object Storage (Dataset storage & access)

Python (Pandas, NumPy, Scikit-learn, Matplotlib)

Jupyter Notebook (Model training & testing)

Machine Learning (Supervised Classification Models)
 IBM Cloud Services Used
Watsonx.ai Studio

IBM Cloud Lite Account

IBM Cloud IAM

IBM Cloud Object Storage
End Users
Electrical power utilities (for real-time fault monitoring)

Power system engineers and maintenance teams

Smart grid operators for improving reliability

Educational & research institutions working on electrical fault analysis
 Key Features
Detects faults in power systems using voltage & current data

Classifies different fault types accurately

Supports real-time analysis for grid stability

Easy-to-use cloud-based interface (IBM Watsonx.ai)

🚀 How It Works
Load Dataset: Electrical measurement data (voltage & current phasors) from Kaggle

Data Preprocessing: Cleaning & normalizing input data

Model Training: Use ML classification algorithms (e.g., Random Forest, SVM, or ANN)

Fault Detection: Model predicts fault type or normal condition

Deployment on IBM Cloud: Deploy trained model via Watsonx.ai Studio

📌 How to Run or Deploy
Log in to IBM Cloud Lite

Open Watsonx.ai Studio

Create a new project and attach Cloud Object Storage

Upload the Kaggle dataset

Train your fault classification model using Jupyter Notebook

Deploy the trained model as an API endpoint

Test the endpoint with real or test input data

🛣 Future Scope
Integration with IoT devices for live grid monitoring

Mobile/web dashboard for real-time fault alerts

Deep learning models (LSTM/ANN) for higher accuracy

Edge deployment in smart grids for faster fault detection

🔗 Useful Links
📊 Dataset - Kaggle: Power System Faults

☁ IBM Cloud Registration

🤖 Watsonx.ai Product Page
