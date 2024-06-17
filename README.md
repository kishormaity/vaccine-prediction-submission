# Vaccine Prediction Project

## Project Overview

This project aims to predict the likelihood of individuals receiving the XYZ flu and seasonal flu vaccines. Using a dataset with various features, we build a machine learning model to predict two target variables:
- `xyz_vaccine`: Whether the respondent received the XYZ flu vaccine.
- `seasonal_vaccine`: Whether the respondent received the seasonal flu vaccine.

## Dataset Description

The dataset includes the following files:
- `training_set_features.csv`: Contains the features for the training set.
- `training_set_labels.csv`: Contains the labels for the training set.
- `test_set_features.csv`: Contains the features for the test set.
- `submission_format.csv`: The format for the submission file.

### Features

The dataset contains 36 columns:
- `respondent_id`: A unique identifier for each respondent.
- Various binary and categorical features such as `xyz_concern`, `xyz_knowledge`, `behavioral_antiviral_meds`, `doctor_recc_xyz`, `health_worker`, `age_group`, `education`, etc.

### Labels

The target variables are binary:
- `xyz_vaccine`: 0 = No, 1 = Yes.
- `seasonal_vaccine`: 0 = No, 1 = Yes.

## Project Structure

- `vaccine_prediction.ipynb`: Jupyter Notebook containing the data exploration, preprocessing, model training, and evaluation.
- `submission.csv`: The submission file containing predicted probabilities for the test set.

## Installation and Usage

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/vaccine-prediction-submission.git
    cd vaccine-prediction-submission
    ```

2. **Install required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open `vaccine_prediction.ipynb` in Jupyter Notebook or Jupyter Lab and run all cells to train the model and generate predictions.

4. **Generate submission file**:
    The notebook will generate a `submission.csv` file with the predicted probabilities.

## Model and Evaluation

We use a Random Forest Classifier to predict the probabilities of receiving the vaccines. The performance is evaluated using the ROC AUC score.

### Steps in the Notebook

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Model Training
5. Model Evaluation
6. Prediction on Test Set
7. Submission File Generation

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to contact me at kishormaity2004@gmail.com.
