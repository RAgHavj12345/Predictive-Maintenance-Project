# 🔧 Predictive Maintenance of Industrial Machinery using IBM Watsonx.ai

This repository contains the assets and documentation for a capstone project focused on predicting industrial machinery failures using machine learning, using IBM Watsonx.ai on the IBM Cloud platform.

---

## 📌 1. Problem Statement

The core objective of this project is to build a robust predictive maintenance system for industrial machinery. The aim is to **predict equipment failures before they occur** by analyzing real-time sensor data. This facilitates **proactive maintenance**, thereby reducing downtime and operational costs.

---

## 💡 2. Proposed Solution

To solve the problem effectively, we developed a **high-accuracy classification model** using **automated machine learning (AutoML)** powered by IBM Watsonx.ai.

This approach leverages the **AutoAI** feature to:

- Automatically preprocess the data  
- Select the most suitable algorithm  
- Build and optimize multiple model pipelines

---

## 🛠️ 3. System Development Approach

The system was developed entirely on the **IBM Cloud**, using the following tools and workflow:

**Platform:** IBM Watsonx.ai  
**Tool:** AutoAI in Watson Studio

### 📂 Workflow:

1. **Data Ingestion**  
   Upload the predictive maintenance dataset to the IBM Cloud project.

2. **Automated Model Building**  
   Configure and execute an AutoAI experiment to evaluate multiple ML pipelines.

3. **Model Selection**  
   Choose the top-performing pipeline based on performance metrics such as accuracy and F1 score.

4. **Deployment**  
   Deploy the best model as a **web service** in a Watsonx deployment space for real-time predictions.

---

## 🧠 4. Algorithm & Model Selection

Among the models evaluated by AutoAI, the **Gradient Boosting Classifier** achieved the best performance, with a leaderboard Rank #1 and an impressive **accuracy of 99.6%**.

---

## 📊 5. Model Performance

The model demonstrated excellent performance on the test set:

- Accurately classified thousands of *"No Failure"* cases  
- Correctly identified critical failure types like:
  - Heat Dissipation Failure
  - Power Failure

### 🔍 Key Predictive Features:

- Torque  
- Rotational Speed  
- Tool Wear

These features were found to be the most influential in predicting machine failure events.

---

## 🚀 6. Deployment & Results

The final model was deployed as a **real-time web service** on IBM Cloud. It was tested successfully with live sensor input, and accurately predicted a *"No Failure"* status with high confidence.

---

## ✅ 7. Conclusion

A highly accurate and production-ready machine learning model was developed for predictive maintenance of industrial machines. Key achievements include:

- Real-time prediction of failure types
- Deployment as a cloud-based web service
- Enabling of **proactive maintenance** strategies
- Reduction in operational disruptions and costs

---

## 🔭 8. Future Scope

Opportunities for future improvements include:

- **Live Data Integration**  
  Integrate the model with real-time machine telemetry.

- **Remaining Useful Life (RUL) Prediction**  
  Extend the solution to predict time-to-failure (RUL).

- **Prescriptive Maintenance**  
  Recommend specific maintenance actions based on predictions.

- **Fleet Dashboard**  
  Build an interactive dashboard to visualize equipment status and health metrics.

---

## 🧪 9. Certifications & Skills Acquired

This project is backed by hands-on training and certifications from IBM SkillsBuild:

- ✅ **Getting Started with Artificial Intelligence**  
- ✅ **Journey to Cloud: Envisioning Your Solution**  
- ✅ **Lab: Retrieval Augmented Generation with LangChain**

### 🖼️ Certificate Previews:

#### Lab: Retrieval Augmented Generation with LangChain  
![LangChain Certificate](certificates/certificate_lab_retrieval.jpg)

#### Getting Started with Artificial Intelligence  
![AI Certificate](certificates/getting_started_ai.jpg)

#### Journey to Cloud: Envisioning Your Solution  
![Cloud Certificate](certificates/journey_to_cloud.jpg)

> ℹ️ Ensure all certificate images are stored in a folder named `certificates/` in the root of your repo.

---

## 📚 10. References

- **Dataset**: [Predictive Maintenance Classification Dataset on Kaggle](https://www.kaggle.com/datasets)  
- **Project Source**: IBM SkillsBuild for Academia in collaboration with Edunet Foundation

---
