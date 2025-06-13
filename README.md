# 🛳️ Titanic Data Analysis with Python

This project is an exploratory data analysis (EDA) of the **Titanic dataset**, using tools like `pandas`, `numpy`, `matplotlib`, and `seaborn`.

> _**Note:** This is not a new project — similar analyses have been conducted by various data science experts. This version serves as a hands-on learning experience._

---

## 📁 Dataset

We used the `titanic` dataset directly from the `seaborn` library:

```python
import seaborn as sns
titanic = sns.load_dataset('titanic')

🔍 Analysis Performed
✅ Data Exploration
Checked data types, null values, and summary statistics.

Filtered and queried the dataset using conditional logic and chained methods.

📊 Grouping & Aggregation
Grouped by class and aggregated age and fare

📈 Pivot Table
Created a pivot table to analyze average age by survival status and class

📉 Data Visualizations

🔹 1. Line Chart: Survival Rate vs Age Group
Binned age into ranges and plotted average survival rate.

Style: bmh, green markers

🔹 2. Multi-Plot Grid (2x2 Layout)
Line plot: Survival rate over age

Scatter plot: Age vs Fare

Bar chart: Average survival rate by age group

Histogram: Distribution of Fare

🔹 3. Box Plot: Fare Distribution by Passenger Class
Compared fare distributions among the 3 classes

📦 Requirements
Install the required libraries using:
pip install pandas matplotlib seaborn numpy

📁 Project Structure

├── titanic_analysis.ipynb      # Main Jupyter notebook
├── plot.png                    # Saved plot image
├── README.md                   # Project documentation

📌 License
This project is for educational and learning purposes.

🙋‍♀️ Author
Samragi Dhakal
linkedin.com/in/samragyedhakal/
📍 Nepal 
