# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Objective

To group mall customers into distinct segments based on their annual income and spending behavior. This helps businesses personalize marketing strategies and enhance customer engagement.

---

## 📂 Dataset

**Features used:**
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

> 📥 Dataset used: `mall_customers.csv`  
> (Synthetic version with 200 rows generated if original not available)

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🧪 Steps Performed

1. **Data Preprocessing**
   - Loaded dataset
   - Checked for nulls and data types
   - Selected relevant features: `Annual Income`, `Spending Score`

2. **Feature Scaling**
   - Standardized features using `StandardScaler`

3. **Finding Optimal Clusters (Elbow Method)**
   - Calculated WCSS (Within-Cluster Sum of Squares)
   - Plotted WCSS vs. number of clusters (1 to 10)
   - Identified elbow point for optimal `k`

4. **K-Means Clustering**
   - Applied KMeans with chosen `k` (e.g., 5)
   - Added cluster labels to the dataset

5. **Visualization**
   - Scatter plot of clusters
   - Color-coded segmentation by clusters

---

## 📊 Results

- Successfully segmented customers into `k` distinct clusters.
- Each cluster represented a unique customer behavior group (e.g., high income & low spenders, low income & high spenders, etc.).
- Visualizations helped interpret and label clusters effectively.

---

## 🧠 Business Use Case

- Helps businesses **target marketing campaigns** more accurately.
- Identify **loyal vs. price-sensitive customers**.
- Personalize offers and improve overall customer satisfaction.

---

## 📈 Sample Visualization

![Cluster Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/K-means_convergence.gif/480px-K-means_convergence.gif)

---

## 🧑‍💻 Author

**Kartik Shripatre**  
Data Science Intern | Digital Marketing Strategist  
GitHub: [github.com/yourusername](https://github.com/kartik-in-cell)

---

## 📬 Questions?

For queries or improvements, feel free to raise an issue or reach out.

