# 🍄 Mushrooms Classification - Kaggle Project

This project is focused on binary classification of mushrooms as either edible (`e`) or poisonous (`p`) based on their physical characteristics. The dataset comes from Kaggle: https://www.kaggle.com/datasets/uciml/mushroom-classification

## 📌 Project Goal

The goal is to build an interpretable and accurate machine learning model that can classify mushrooms using features like cap shape, odor, gill color, and more. The target variable is `class`, where:
- `e` = edible
- `p` = poisonous

## 🧠 Technologies Used

- Python 3.10+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## 📁 Project Structure

mushrooms_kaggle/
├── data/
│ └── mushrooms.csv # Dataset
├── notebooks/
│ ├── 01_data_analysis.ipynb # Exploratory Data Analysis (EDA)
│ ├── 02_preprocessing.ipynb # Data Preprocessing
│ └── 03_modeling.ipynb # Model Training and Evaluation
├── models/ # Saved models (if any)
├── requirements.txt # Project dependencies
└── README.md # Project description

markdown
Копировать
Редактировать

## 🔍 Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Examine feature distributions  
   - Identify important variables  
   - Use visualizations like heatmaps, bar plots, count plots

2. **Data Preprocessing**  
   - Encode categorical features using Label Encoding  
   - Split dataset into training and testing sets

3. **Modeling**  
   - Train models such as Decision Tree, Random Forest, K-Nearest Neighbors  
   - Compare model performance using accuracy and cross-validation

4. **Evaluation**  
   - Evaluate models using accuracy score and confusion matrix  
   - Visualize feature importance  
   - Perform cross-validation for robustness

## 📈 Results

- Models achieved over 95% accuracy on test data  
- Random Forest performed best in terms of accuracy and interpretability  
- Most important features: `odor`, `gill-color`, `spore-print-color`

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/SergKhachikyan/mushrooms_kaggle.git
```
```
cd mushrooms_kaggle
```

2.Install dependencies:
```
pip install -r requirements.txt
```
Open Jupyter Notebook and run the notebooks in order:

01_data_analysis.ipynb

02_preprocessing.ipynb

03_modeling.ipynb
