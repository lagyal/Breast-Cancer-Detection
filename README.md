**Breast Cancer Detection**

This project is a machine learning model designed to detect breast cancer using the "Breast Cancer Wisconsin Data" from Kaggle. The model preprocesses the dataset, explores the features, and builds a predictive classifier to distinguish between malignant and benign tumors.

**Dataset**

The dataset used in this project can be found on Kaggle: Breast Cancer Wisconsin Data.

**Dataset Features:**

**ID**: Identifier of each record.

**Diagnosis**: Malignant (M) or Benign (B).

**Features**: Several numerical attributes relating to the size, shape, and texture of the cell nuclei.

**Project Structure**

Breast Cancer Detection.ipynb: Jupyter notebook containing the code for data preprocessing, exploratory data analysis (EDA), and model training.

**Steps Covered**

**Importing Libraries**: Key libraries such as pandas, numpy, seaborn, and matplotlib are used for data manipulation and visualization.

**Data Preprocessing**: Prepares the data by handling missing values, encoding categorical features, and scaling the data.

**Exploratory Data Analysis (EDA)**: Analyzes the dataset to gain insights into the distribution of features and their relationship with the target variable (Diagnosis).

**Model Building**: Implements various machine learning algorithms (such as Logistic Regression, Decision Trees, etc.) to predict whether a tumor is malignant or benign.

**Model Evaluation**: Evaluates the models using metrics like accuracy, precision, recall, and F1-score.

How to Run

Clone this repository:

bash

Copy code

git clone https://github.com/lagyal/breast-cancer-detection.git

Install the required libraries:

bash

Copy code

pip install -r requirements.txt

Run the Jupyter notebook to see the results:

bash

Copy code

jupyter notebook Breast\ Cancer\ Detection.ipynb

**Libraries Used**

**pandas**

**numpy**

**seaborn**

**matplotlib**

**sklearn**

License

This project is licensed under the **MIT License** - see the LICENSE file for details.

Acknowledgments

The dataset is provided by the UCI Machine Learning repository and hosted on Kaggle.
