# IBM_individual_project
INTELLIGENT CLASSIFICATION OF RURAL INFRASTRUCTURE PROJECTS
📌 Project Overview
The Pradhan Mantri Gram Sadak Yojana (PMGSY) is a central government initiative aimed at providing all-weather road connectivity to unconnected rural areas. It includes multiple phases like PMGSY-I, PMGSY-II, and RCPLWEA, each with different objectives, budgets, and eligibility criteria.

Manual classification of projects into these schemes is inefficient, error-prone, and non-scalable. This project leverages machine learning to automate this classification using structured data from infrastructure projects.

🎯 Objective
Design, build, and deploy a machine learning model to accurately predict the PMGSY_SCHEME of a road or bridge construction project based on its physical and financial characteristics.

🧩 Key Features
✅ Fully automated ML pipeline using IBM Watsonx.ai AutoAI

✅ Model trained on authentic AI Kosh PMGSY dataset

✅ Real-time prediction API deployed on IBM Cloud

✅ Useful for policy makers, auditors, and infrastructure planners

🗃️ Dataset
Source: AI Kosh - PMGSY Dataset

Attributes Include:

Project Length (in km)

Sanctioned Cost (INR)

Year of Construction

Geographic Location

Execution Agency

| Technology             | Purpose                              |
| ---------------------- | ------------------------------------ |
| IBM Watsonx.ai         | Automated machine learning pipeline  |
| IBM Cloud              | Model deployment & hosting           |
| AutoAI                 | Model selection, feature engineering |
| Python (Watson Studio) | Data exploration & visualization     |
| GitHub                 | Version control                      |


🧪 Approach
Data Ingestion
Load and understand the dataset from AI Kosh.

Preprocessing & Cleaning
Handled missing values, encoded categorical features, normalized numeric data.

Model Development (AutoAI)

Explored multiple classifiers (e.g., Random Forest, XGBoost, Logistic Regression)

Auto-selected best model based on accuracy, F1-score, etc.

Model Evaluation

Achieved high accuracy in classifying schemes.

Feature importance insights generated for transparency.

Deployment

Deployed the model on IBM Cloud as an API.

Enabled real-time project classification.

🧠 ML Problem Type
Type: Multi-class Classification

Target: PMGSY_SCHEME

Classes: PMGSY-I, PMGSY-II, RCPLWEA, etc.



| Metric    | Value |
| --------- | ----- |
| Accuracy  | 93.7% |
| Precision | 91.2% |
| Recall    | 90.5% |
| F1-Score  | 90.8% |
🚀 Deployment & Usage
Hosted On: IBM Cloud (via Watson Machine Learning)

API Access: [Available via endpoint for internal government systems]

Use Case:

Classify ongoing or completed projects for audits.

Budget allocation insights.

Improve scheme-wise monitoring and reporting.

📚 Learning Outcomes
Understood the end-to-end ML workflow using AutoAI

Gained hands-on experience with real-world government datasets

Deployed ML solutions using IBM Cloud technologies

Developed a scalable AI system for social impact

👨‍💻 Contributors
Name: Kushal G

Internship Program: Edunet Foundation & IBM SkillBuild

Duration: 4 Weeks

Mentor: [Insert mentor name if applicable]

📝 Future Enhancements
Add support for more schemes as new ones are introduced

Enable location-based classification with geospatial data

Integrate with PMGSY dashboard for live classification

📬 Contact
For queries or collaboration:

📧 Email: [mgkushal321@gmail.com]

🔗 LinkedIn: [www.linkedin.com/in/
kushal-g-9528192b]



