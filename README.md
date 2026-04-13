# 🛍️ Customer Segmentation using K-Means

## 👨‍💻 Author
**Yuval Varke**  

---

## 📌 Project Description
This project applies **K-Means Clustering** to segment customers of a retail store into distinct groups based on their **Annual Income** and **Spending Score**.  

Customer segmentation is a key strategy in marketing and helps businesses:
- Identify different types of customers  
- Create targeted marketing campaigns  
- Design loyalty programs  
- Personalize offers and discounts  

---

## 📂 Dataset
- **Name:** Customer Segmentation Tutorial in Python  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **File Used:** `Mall_Customers.csv`  

**Dataset Columns:**
- `CustomerID` → Unique customer ID  
- `Gender` → Male / Female  
- `Age` → Age of the customer  
- `Annual Income (k$)` → Annual income in thousand dollars  
- `Spending Score (1-100)` → Spending score assigned by the mall  

---

## ⚙️ Steps Involved
1. **Load the dataset** using Pandas.  
2. **Select features** → `Annual Income` & `Spending Score`.  
3. **Elbow Method** → Determine optimal number of clusters (k).  
4. **Apply K-Means Clustering** with chosen k.  
5. **Visualize clusters** using scatter plots with centroids.  
6. **Interpret customer groups**.  

---

## 📊 Visualizations
### Elbow Method
Helps to choose the optimal number of clusters (k). 

### Customer Segments
Clusters customers into groups such as:  
- **High Income – High Spending (Luxury Shoppers 💎)**  
- **Low Income – Low Spending (Budget Customers 💵)**  
- **High Income – Low Spending (Careful Customers 🧐)**  
- **Medium Income – Medium Spending (Average Customers 🙂)**  
- **Low Income – High Spending (Impulsive Customers ⚡)**  


---

## 🚀 Tech Stack
- **Python**  
- **Pandas** → Data handling  
- **Matplotlib / Seaborn** → Visualization  
- **Scikit-Learn** → K-Means Clustering  

---

## 🏆 Results
The K-Means algorithm successfully divided customers into **5 meaningful groups**, helping the retail store better understand customer behaviors and design targeted strategies.  

---

   