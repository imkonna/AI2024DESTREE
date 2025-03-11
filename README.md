
---

## 🛠 Technologies & Libraries Used
- **Programming Language:** Python  
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning Models:** Decision Trees, Random Forest  
- **Feature Engineering & Analysis:** Grid Search CV, Feature Importance, Confusion Matrix  

---

## 🔍 Dataset & Problem Statement

- **Dataset Source:** [Kaggle - Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)  
- **Goal:** To classify whether a given water sample is **potable (safe to drink) or non-potable** based on its chemical attributes.  
- **Number of Samples:** 3,276  
- **Number of Features:** 9 (pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity)  

---

## 🏆 Implementation Overview

### **1️⃣ Data Preprocessing & Visualization**
- **Exploratory Data Analysis (EDA)**: Histograms, bar charts, and scatter plots to analyze feature distributions.  
- **Handling Missing Values**: Identified missing values and assessed data quality.  
- **Feature Engineering**: Computed feature importance using **Decision Trees & Random Forest**.  

### **2️⃣ Decision Tree Model**
- Trained a **Decision Tree Classifier** to predict water potability.  
- Tuned hyperparameters (**max depth, min samples split, pruning**) using **Grid Search CV**.  
- Achieved **X% accuracy** on the test set.  
- Visualized the **decision tree structure**.

### **3️⃣ Random Forest Model**
- Trained a **Random Forest Classifier** with different tree counts (50, 100, 200).  
- Compared performance with Decision Tree.  
- Analyzed **feature importance** to identify key water quality indicators.  

### **4️⃣ Model Comparison & Insights**
| Model          | Test Accuracy | Key Findings |
|---------------|--------------|-------------|
| **Decision Tree** | **X%** | More interpretable, but prone to overfitting. |
| **Random Forest** | **X%** | More robust, better generalization, higher accuracy. |

📌 *Key Conclusion:* **Random Forest outperformed Decision Trees, but Decision Trees offer better interpretability for legal and regulatory purposes.*

---

## 📊 Results & Key Findings

- **The most important chemical properties affecting potability were:**  
  - **pH Level**
  - **Hardness**
  - **Solids Concentration**
  - **Chloramine Levels**
  - **Sulfate Levels**
- **Decision Trees vs. Random Forest:** While **Random Forest achieved higher accuracy**, Decision Trees were more interpretable.  
- **Legal Considerations:** For regulatory approval, a Decision Tree model may be **safer** due to its transparency in decision-making.  

---

## 🔧 How to Run the Code

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/yourusername/Water-Potability-ML.git
cd Water-Potability-ML
