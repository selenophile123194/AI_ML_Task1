# 🌸 Task 1: Exploring and Visualizing the Iris Dataset

## 📌 Objective
The goal of this task is to learn how to load, inspect, and visualize a simple dataset to understand data trends, distributions, and relationships between features.

## 📊 Dataset
- **Name:** Iris Dataset  
- **Source:** Seaborn built-in dataset (can also be found on UCI Machine Learning Repository)  
- **Number of Records:** 150  
- **Features:**
  - `sepal_length` (cm)
  - `sepal_width` (cm)
  - `petal_length` (cm)
  - `petal_width` (cm)
  - `species` (Setosa, Versicolor, Virginica)

## 🛠 Steps Performed
1. **Data Loading**
   - Imported dataset using Seaborn's `load_dataset("iris")`.
   - Checked dataset shape, column names, and previewed first 5 rows.
   
2. **Data Inspection**
   - Used `.info()` to see data types and null values.
   - Used `.describe()` for summary statistics.

3. **Data Visualization**
   - **Scatter Plots:** To show relationships between sepal and petal dimensions.
   - **Histograms:** To view the distribution of each feature.
   - **Box Plots:** To identify potential outliers.

## 🧠 Key Insights
- Petal measurements show clear separation between species.
- Setosa is distinctly different from the other two species.
- Some overlap exists between Versicolor and Virginica in sepal measurements.
- Sepal width has a slightly wider spread compared to other features.

## 📈 Visualizations Included
- Sepal Length vs Sepal Width scatter plot
- Petal Length vs Petal Width scatter plot
- Feature histograms
- Boxplots for outlier detection

## 📂 Files in This Folder
- `Task1_Iris_Analysis.ipynb` — Jupyter Notebook with complete code and explanations.
- `README.md` — This file, describing the project.

## 🏷 Tools & Libraries Used
- **Python** (3.8+)
- **Pandas** — Data loading and inspection
- **Matplotlib** — Data visualization
- **Seaborn** — Enhanced plots and styling

## ✅ Conclusion
The Iris dataset is an excellent starting point for learning data analysis and visualization. Clear patterns emerge in petal dimensions, which can later be used for species classification.

## 📚 References
1. **Seaborn Documentation — Iris Dataset**  
   🔗 [https://seaborn.pydata.org/data.html#iris-dataset](https://seaborn.pydata.org/data.html#iris-dataset)  
2. **Original Iris Dataset (UCI Machine Learning Repository)**  
   🔗 [https://archive.ics.uci.edu/dataset/53/iris](https://archive.ics.uci.edu/dataset/53/iris)

