# EDIT-School-Projects
Projects developed during my Data Science and Data Analytics course.

## Car Data Analysis - Module 4 Session 3

This project is an exploratory data analysis based on a car dataset. The main focus is on identifying **outliers** and preparing the data for future analyses. The work was carried out as part of Module 4, Exploratory Data Analysis, Session 3 of the Data Science and Business Analytics course.

### 📂 Notebook Structure

#### Part I - Outliers

- Import of essential libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.
- Loading the dataset `carros3_AnaCintiaOliveira.csv`.
- Preliminary analysis using `.info()` and `.describe()`.
- Initial data cleaning: removal of non-essential columns (`width_std`, `mean_width`, `height_log`, `price_decile`).
- Outlier analysis using statistical measures and visualizations — IQR, standardization, and deciles.
- Comparison and analysis of variable distribution, considering applied standardization.
- Assessment of the impact on variable correlation.

#### Part II

- Conversion and creation of variables (numeric - num-of-doors, dummy variables, decimal formatting).
- Range calculation and creation of price levels: high, medium, and low.

#### Part III

- Data exploration using boxplots, bar charts, pie charts, scatter plots, and heatmaps.

## 🧰 Technologies Used

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- Google Colab / Jupyter Notebook

## ▶️ How to Run

1. Make sure you have Python installed or access Google Colab.
2. Install the required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3. Open Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Run the file `Modulo_4_Sessão3_Exercicio_1_Ana_Cintia_Oliveira_.ipynb`.

## 👩‍💻 Author

Project developed by **Ana Cíntia Oliveira**.

---

> This project is part of an academic exercise and can be expanded with visualizations, modeling, or more in-depth conclusions.
