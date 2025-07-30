# 🔧 Predictive Maintenance of Industrial Machinery using IBM Watsonx.ai

This repository contains the assets and documentation for a capstone project focused on predicting industrial machinery failures using machine learning on the IBM Cloud platform.

---

## 1. 📌 Problem Statement

The primary challenge is to develop a robust predictive maintenance model for industrial machinery. The goal is to **anticipate equipment failures before they occur** by analyzing real-time sensor data. This enables **proactive maintenance**, helping to reduce operational costs and minimize machine downtime.

---

## 2. 💡 Proposed Solution

To address this challenge, we developed a **high-accuracy classification model** using an **automated machine learning (AutoML)** approach. This solution leverages the **AutoAI feature within IBM Watsonx.ai** to automatically:

- Preprocess data  
- Select the best algorithm  
- Build an optimized model ready for deployment

---

## 3. 🛠️ System Development Approach

The entire project was implemented on **IBM Cloud**, following these steps:

**Platform:** IBM Watsonx.ai  
**Tool Used:** AutoAI in Watson Studio

**Workflow:**

1. **Data Ingestion**: Upload the predictive maintenance dataset to the IBM Cloud project.
2. **Automated Model Building**: Configure and run an AutoAI experiment to generate and evaluate multiple model pipelines.
3. **Model Selection**: Choose the top-ranked pipeline based on performance metrics.
4. **Deployment**: Promote the saved model to a deployment space and create an online web service for real-time predictions.

---

## 4. 🧠 Algorithm & Model Selection

AutoAI evaluated multiple algorithms and selected the **Gradient Boosting Classifier** as the best-performing model. It ranked **#1** on the leaderboard with an **accuracy of 99.6%**.

---

## 5. 📊 Model Performance

The **confusion matrix** demonstrated the model’s high effectiveness:

- Correctly predicted thousands of *"No Failure"* instances
- Accurately identified failure types like:
  - Heat Dissipation Failure
  - Power Failure

**Key Predictive Features:**

- Torque  
- Rotational Speed  
- Tool Wear

These features had the highest impact on predicting machine failures.

---

## 6. 🚀 Deployment & Results

The final model was deployed as a **live web service** on IBM Cloud. In a real-time test, the model correctly predicted *"No Failure"* with high confidence based on incoming sensor data.

---

## 7. ✅ Conclusion

A **high-accuracy ML model** was built and deployed for predictive maintenance. This model can effectively:

- Predict multiple failure types from real-time sensor data
- Enable **proactive maintenance**
- Reduce operational costs
- Increase machinery uptime

---

## 8. 🔭 Future Scope

- **Real-time Integration**: Connect the model to live machinery data streams.
- **Predicting “Time to Failure”**: Extend the model to estimate Remaining Useful Life (RUL).
- **Prescriptive Analytics**: Recommend specific maintenance actions based on predictions.
- **Interactive Dashboard**: Visualize health status across machines using dashboards.

---

## 9. 🧪 Certifications & Skills

This project was supported by the following IBM SkillsBuild programs:

- **Getting Started with Artificial Intelligence**  
- **Journey to Cloud: Envisioning Your Solution**  
- **Lab: Retrieval Augmented Generation with LangChain**

### 🖼️ Certificate Previews:

#### ✅ Lab: Retrieval Augmented Generation with LangChain  
![LangChain Certificate](assets/certificate1.png)

#### ✅ Getting Started with Artificial Intelligence  
![AI Certificate](assets/certificate2.png)

#### ✅ Journey to Cloud: Envisioning Your Solution  
![Cloud Certificate](assets/certificate3.png)

---

## 10. 📚 References

- **Dataset**: [Predictive Maintenance Classification Dataset on Kaggle](https://www.kaggle.com/datasets)  
- **Project Source**: Provided by **IBM SkillsBuild for Academia** & **Edunet Foundation**

---
