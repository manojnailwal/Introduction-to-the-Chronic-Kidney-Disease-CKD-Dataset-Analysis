# Chronic Kidney Disease (CKD) Dataset Analysis

## 📊 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Chronic Kidney Disease (CKD) dataset**. The dataset contains vital information about patients, including their **age**, **blood pressure**, **blood sugar levels**, and other medical factors. The goal of this analysis is to uncover patterns, relationships, and insights that can aid in the **early diagnosis** of CKD.

By performing this analysis, we explore important features, check for missing or duplicate data, and visualize various statistical relationships to better understand the underlying trends in the dataset.

---

## 🛠️ Tools & Libraries Used
This project utilizes several Python libraries for data manipulation, visualization, and machine learning. Here are the key tools used:
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For creating static plots and visualizations.
- **Seaborn**: For statistical data visualizations.
- **Plotly**: For interactive visualizations.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For machine learning modeling and preprocessing.

---

## 📈 Key Steps in the Analysis
1. **Data Collection**: The dataset was collected from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease).
2. **Data Cleaning**:
   - Checking and handling **null values**.
   - Removing **duplicate rows**.
   - **Changing data types** for categorical and numerical columns.
3. **Exploratory Data Analysis (EDA)**:
   - Univariate analysis with histograms, box plots, and violin plots.
   - Bivariate and multivariate analysis using **correlation heatmaps** and **pair plots**.
   - Identifying and handling **outliers** using IQR (Interquartile Range).
   - Visualizing relationships with **scatter plots**, **pie charts**, and **swarm plots**.
4. **Feature Engineering**: Creating new features to improve model performance and analyzing their importance.

---

## 🧰 Setup and Installation
To run the project locally, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/manojnailwal/CKD-EDA-Analysis.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd CKD-EDA-Analysis
   ```

3. **Install dependencies**:
   It's recommended to create a virtual environment before installing the dependencies. You can use **`requirements.txt`** to install all necessary libraries.
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter notebook**:
   Launch Jupyter Notebook and open the `CKD_EDA_Analysis.ipynb` file:
   ```bash
   jupyter notebook
   ```

---

## 📑 Dataset Information
The dataset consists of the following columns:

- **id**: Unique identifier for each patient.
- **age**: Age of the patient.
- **bp**: Blood pressure.
- **sg**: Specific gravity of urine.
- **al**: Albumin levels in urine.
- **su**: Sugar levels in urine.
- **rbc**: Red blood cells in urine.
- **pc**: Pus cell in urine.
- **pcc**: Pus cell clumps in urine.
- **ba**: Bacteria in urine.
- **bgr**: Blood glucose random.
- **bu**: Blood urea.
- **sc**: Serum creatinine.
- **sod**: Sodium in blood.
- **pot**: Potassium in blood.
- **hemo**: Hemoglobin level.
- **pcv**: Packed cell volume.
- **wc**: White blood cell count.
- **rc**: Red blood cell count.
- **htn**: Hypertension (yes/no).
- **dm**: Diabetes (yes/no).
- **cad**: Coronary artery disease (yes/no).
- **appet**: Appetite status (good/poor).
- **pe**: Pedal edema (yes/no).
- **ane**: Anemia (yes/no).
- **classification**: Whether the patient has CKD (yes/no).

---

## 🔍 Visualizations
Some of the key visualizations generated during the analysis include:

- **Correlation Heatmap**: To examine correlations between different features.
- **Pair Plots**: To visualize relationships between pairs of features.
- **Boxplots & Violin Plots**: To identify outliers and distribution of features.
- **Bar Charts & Pie Charts**: To visualize categorical data.

Examples of the output visualizations can be found in the Jupyter notebook.

---

## 💡 Key Findings
- There is a **strong correlation** between certain features like **age**, **blood pressure**, and **serum creatinine**.
- **Outliers** were detected in features such as **blood glucose**, which may require further preprocessing for modeling.
- Several **missing values** were imputed with **mean/median** values depending on the feature.

---

## 🤝 Contributing
If you'd like to contribute to this project, feel free to fork the repository, submit a pull request, or open an issue to suggest improvements or report bugs.

---

## 📬 Contact & Author Information
**Author**: Manoj Nailwal  
📧 **Email**: [manojnailwal1234567@gmail.com](mailto:manojnailwal1234567@gmail.com)  
🔗 **LinkedIn**: [linkedin.com/in/manoj-nailwal-70988024a](https://linkedin.com/in/manoj-nailwal-70988024a)  
🐙 **GitHub**: [github.com/manojnailwal](https://github.com/manojnailwal)

---

**Thank you for exploring this project!**  
Feel free to reach out for feedback, suggestions, or collaborations.
```

### Key Sections Explained:

1. **Project Overview**: A concise introduction to what the project is about, with the goal and context of the CKD dataset.
2. **Tools & Libraries Used**: A list of the tools and libraries you used, which can help other developers or collaborators understand the technical stack.
3. **Key Steps**: A bullet-point list of the steps you followed during the EDA process, from data cleaning to visualizations.
4. **Setup Instructions**: How to set up the project locally, including cloning the repo, installing dependencies, and running the Jupyter notebook.
5. **Dataset Information**: A detailed list of the columns in the dataset for better understanding and clarity.
6. **Visualizations**: A summary of the types of visualizations produced during the analysis.
7. **Key Findings**: An overview of the important insights derived from the EDA process.
8. **Contributing**: A section inviting others to contribute to the project, which is useful for open-source collaborations.
9. **Contact Information**: Your contact info for feedback or collaboration, including links to your email, LinkedIn, and GitHub profiles.

### Benefits:
- **Attractive**: The README is well-structured with clear headings and sections.
- **Informative**: Provides all necessary information for someone to understand, replicate, or contribute to the project.
- **Interactive**: Links to your social media and email are clickable for easy outreach.
