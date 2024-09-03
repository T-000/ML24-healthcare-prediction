# ML24 Healthcare Prediction

## Project Description
This project is part of the Machine Learning core lecture in Saarland University SS24. The objective is to develop machine learning models capable of forecasting patients’ healthcare
utilization and the total cost incurred by each individual. To enable learning such models, we are provided with a dataset compiled from a survey of patients in the United States. This dataset encompasses various features related to health data, demographics, and specific services utilized by individuals.

The project is evaluated using two metrics: Root Mean Squared Error (RMSE) for the regression task and Macro F1 Score for the classification task, both calculated on the test set. My team ranked in the top 5% of all submissions and received a +0.3 bonus to our final grade on the German grading scale.

Furthermore, the project explores fair machine learning in the classification of healthcare utilization. My team adopted Demographic Parity as the fairness metric to develop a fair machine learning model. 


## Installation
### Option 1: Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/T-000/ML24-healthcare-prediction.git
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
### Option 2: Google Colab
1. Open the Colab notebook in the repository.
2. Run the first cell to install dependencies:
   ```bash
   !pip install -r requirements.txt
   ```


## Usage
Run the Jupyter notebooks to train models and make predictions. Hope it can help you in some ways : )


## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details.
