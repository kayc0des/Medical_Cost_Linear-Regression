## Medical Cost Linear Regression Model

This repository contains code to develop a linear regression model to predict medical insurance charges for individuals based on various factors such as age, sex, BMI, number of children, smoking status, and region.

### Dataset
The dataset used for this project is stored in a CSV file named `insurance.csv` under the `data` folder. The dataset contains the following columns:

1. **age**: Age of the individual.
2. **sex**: Gender of the individual (male or female).
3. **bmi**: Body Mass Index (BMI) of the individual.
4. **children**: Number of children/dependents covered by the insurance.
5. **smoker**: Smoking status of the individual (yes or no).
6. **region**: Region of the individual (northeast, northwest, southeast, southwest).
7. **charges**: Medical insurance charges billed to the individual.

### Setup
To run the code and develop the linear regression model, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required dependencies listed in `requirements.txt` using the following command:

4. Navigate to the directory containing the cloned repository.

### Usage
Execute the notebook `linear_regression.ipynb` to train the linear regression model and make predictions. You can adjust the parameters and hyperparameters within the script according to your requirements.

### Files
- **data/insurance.csv**: The dataset containing medical insurance data.
- **linear_regression.ipynb**: Python Notebook to train the linear regression model.
- **README.md**: This README file providing information about the project.

### Dependencies
- Python 3.x
- pandas
- scikit-learn

### Notes
- This model assumes a linear relationship between the independent variables and the medical charges.
- Model performance metrics such as mean squared error, R-squared, etc., are calculated and can be found in the output of the script.

### Contributors
- Kingsley Budu Boafo

Feel free to contribute to and improve upon this project! If you have any questions or suggestions, please contact kingsleybudu50@gmail.com