Road Casualty Statistics Analysis
Overview
This Python script performs an analysis on road casualty statistics using the DfT Road Casualty Statistics dataset. It includes data cleaning, exploration, and the development of a regression model to predict casualty severity. The script utilizes popular libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, and Plotly.

Getting Started
Prerequisites
Python 3
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly
bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn plotly
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/AminHeidariSardabi/dft-road-casualty-statistics-casualty-provisional-mid-year-unvalidated-2022.git
Change into the project directory:
bash
Copy code
cd your_repository
Run the script:
bash
Copy code
python your_script.py
Usage
The script starts by importing necessary libraries and loading the dataset (dft-road-casualty-statistics-casualty-provisional-mid-year-unvalidated-2022.csv).

Data cleaning is performed to handle missing values and remove redundant columns.

Duplicate rows are checked and removed.

Several columns with invalid or missing values are filtered and dropped from the dataset.

A summary table is generated to display the most repeated values in each column.

Visualizations are created to explore the distribution of data, such as histograms for the age of casualties and count plots for casualty class.

Additional geographical features are created by extracting information from the 'lsoa_of_casualty' column.

A regression model is created to predict casualty severity using various algorithms, including Linear Regression, Decision Tree, Random Forest, Gradient Boosting, Support Vector Machine, and Neural Network.

Model evaluation results, including Mean Squared Error (MSE), are displayed, and the best-performing model is identified.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
The dataset used in this project is provided by UK Goverment.
