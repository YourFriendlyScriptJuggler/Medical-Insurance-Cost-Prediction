 
# Medical Insurance Cost Prediction

This project predicts medical insurance costs using regression techniques on a public dataset. By analyzing features such as age, sex, BMI, number of children, smoking status, and residential region, the model estimates the insurance charges for an individual.

## Dataset

The dataset used is typically referred to as the "Medical Cost Personal Dataset" (`insurance.csv`). It includes the following columns:

- `age`: Age of the individual.
- `sex`: Gender (`male`, `female`).
- `bmi`: Body Mass Index (numeric).
- `children`: Number of children/dependents covered by insurance.
- `smoker`: Smoking status (`yes`, `no`).
- `region`: Residential region in the US (`northeast`, `southeast`, `southwest`, `northwest`).
- `charges`: Individual medical costs billed by health insurance (target variable).

## Project Workflow

1. **Import Dependencies**  
   Utilizes Python libraries such as pandas, NumPy, matplotlib, seaborn, and scikit-learn.

2. **Data Collection & Analysis**  
   - Loads the dataset.
   - Performs data exploration: checking data types, missing values, and statistical summaries.
   - Visualizes feature relationships with target variable.

3. **Data Preprocessing**  
   - Encodes categorical variables to numeric values.
   - Splits data into features (X) and target (`charges`), then into training and test sets.

4. **Model Training**  
   - Trains a Linear Regression model to predict insurance charges.

5. **Model Evaluation**  
   - Evaluates performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

6. **Prediction**  
   - The model can estimate insurance charges for new or custom input data.


## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/medical-insurance-cost-prediction.git
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Dataset**
   - Place `insurance.csv` in the project directory.

4. **Run the Notebook**
   - Open and execute the Jupyter notebook:
     ```bash
     jupyter notebook Medical_Insurance_Cost_Prediction.ipynb
     ```

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the requirements using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Results

The implemented Linear Regression model achieves reasonable predictive performance. Model metrics such as MAE, MSE, and R² Score are used to assess regression accuracy. The model shows that smoking status, BMI, and age are significant cost drivers.

## Project Structure

```
.
├── insurance.csv
├── Medical_Insurance_Cost_Prediction.ipynb
├── README.md

```

## License

This project is for educational purposes. The dataset is publicly available, typically under open data terms.


