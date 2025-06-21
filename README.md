# Titanic Survival Data Analysis 🚢🔍

![Titanic Survival Analysis](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Titanic_%28RMS_Titanic%29.jpg/800px-Titanic_%28RMS_Titanic%29.jpg)

Welcome to the **Titanic Survival Data Analysis** repository! This project aims to analyze passenger data from the Titanic to predict survival based on various features such as age, gender, class, and fare. 

For more details on our latest updates, please visit our [Releases section](https://github.com/Ferreira198/Titanic-Survival-Data-Analysis/releases).

## Table of Contents

1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Analysis](#analysis)
6. [Machine Learning Models](#machine-learning-models)
7. [Data Visualization](#data-visualization)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Introduction

The Titanic was a passenger liner that sank in the North Atlantic Ocean after hitting an iceberg. This tragedy led to the loss of more than 1,500 lives. Understanding the factors that influenced survival can provide insights into social and economic conditions of the time. This project utilizes data analysis techniques to predict survival rates based on various passenger features.

## Data Description

The dataset includes various attributes of the passengers, such as:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = First, 2 = Second, 3 = Third)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Fare paid for the ticket
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Installation

To set up this project on your local machine, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ferreira198/Titanic-Survival-Data-Analysis.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Titanic-Survival-Data-Analysis
   ```

3. **Install the required packages:**

   You can install the necessary Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. **Open the Jupyter Notebook:**

   Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

## Usage

Once you have set up the environment, you can start analyzing the data. Open the Jupyter Notebook file named `Titanic_Survival_Analysis.ipynb` and follow the instructions within to explore the dataset.

## Analysis

The analysis includes:

- **Descriptive Statistics**: Understanding the basic characteristics of the data.
- **Data Cleaning**: Handling missing values and correcting data types.
- **Feature Engineering**: Creating new features that may help improve model performance.
  
You can run the analysis cells in the notebook to see the results in real-time.

## Machine Learning Models

This project implements various machine learning models to predict survival rates:

- **Logistic Regression**: A basic yet effective model for binary classification.
- **Decision Trees**: A model that splits the data into branches to make predictions.
- **Random Forest**: An ensemble method that combines multiple decision trees.
- **Support Vector Machines**: A model that finds the optimal hyperplane for classification.

Each model's performance is evaluated using metrics like accuracy, precision, and recall.

## Data Visualization

Visualizing data helps in understanding patterns and trends. This project uses libraries like Matplotlib and Plotly to create informative plots. Some visualizations include:

- **Survival Rate by Gender**: A bar chart showing survival rates for male and female passengers.
- **Age Distribution**: A histogram depicting the age distribution of passengers.
- **Fare Distribution**: A box plot showing fare prices across different classes.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request. 

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out to the repository owner:

- **Name**: [Your Name]
- **Email**: [your.email@example.com]

You can also check our [Releases section](https://github.com/Ferreira198/Titanic-Survival-Data-Analysis/releases) for the latest updates and downloadable files.

Thank you for visiting the Titanic Survival Data Analysis repository!