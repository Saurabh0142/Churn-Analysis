# 📊 Telco Customer Churn Analysis

This project provides a comprehensive analysis of customer churn at a telecom company. Using Python libraries like Pandas, Matplotlib, and Seaborn, the analysis uncovers patterns that can help reduce customer attrition and improve retention strategies.

---

## 📌 Dataset Overview

- **Total Customers**: 7,043  
- **Features**: Demographics, subscription details, account information, churn status  
- **Goal**: Identify key factors contributing to customer churn

---

## 🔍 Key Findings

### ✅ Overall Churn Rate

- **Churned Customers**: 1,869  
- **Churn Rate**: **~26.5%**

---

### 👵 Senior Citizens & Churn

- **Senior Citizens (Age 65+)**: ~16% of all customers  
- **Churn Rate Among Seniors**: **~42%**  
- Significantly higher than the average churn rate, indicating the need for tailored services.

---

### ⏳ Tenure & Churn

- **< 12 Months Tenure**: Very high churn, especially in the **first 2 months (~60%)**
- **> 24 Months Tenure**: Churn drops to **<10%**
- Suggests strong customer loyalty among long-term users.

---

### 🌐 Internet and Additional Services

Analysis across different service columns (`PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`) reveals:

#### Internet Service Type
| Service Type | Churn Rate |
|--------------|------------|
| Fiber Optic  | ~42%       |
| DSL          | ~19%       |
| No Service   | Very Low   |

#### Add-On Services
| Service             | Without Service | With Service |
|---------------------|-----------------|--------------|
| Online Security     | ~31% churn      | ~15% churn   |
| Online Backup       | ~28% churn      | ~16% churn   |
| Tech Support        | ~30% churn      | ~14% churn   |
| Device Protection   | ~29% churn      | ~17% churn   |
| StreamingTV         | ~27% churn      | ~18% churn   |
| StreamingMovies     | ~26% churn      | ~17% churn   |

Customers **without these services are 1.5–2x more likely to churn**.

---

## 📈 Visualizations

- Plotted **grouped count plots** using `sns.countplot()` across service-based features.
- Subplots are arranged in a **3x3 grid** for quick comparison.
- Visualization clearly shows churn disparity based on service availability.

---

## 💡 Recommendations

- 🎯 **Target New Customers**: Enhance onboarding experience to reduce churn in the first year.
- 🔒 **Promote Security & Support Services**: Strong retention correlation.
- 👵 **Create Senior Plans**: Address specific needs of elderly users.
- 🚧 **Investigate Fiber Optic Service**: High churn indicates potential service or pricing issues.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

