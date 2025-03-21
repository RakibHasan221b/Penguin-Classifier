# Penguin-Classifier
**Files and Descriptions:**

1 .github/workflows/daily_prediction.yml: GitHub Actions workflow file that automates the daily prediction task. It runs the prediction script every day at 7:30 AM CET.

2. Data Cleaning and Feature Engineering/: This folder contains Python scripts related to the cleaning and feature engineering of the penguin dataset.

3. Feature_engineering.py: Handles the feature extraction and transformation for the dataset.
4. clean_data.py: Contains the logic for cleaning the raw penguin data, handling missing values, and ensuring the data is ready for model training.
5. Data Download and Database/: This folder contains scripts for downloading and storing penguin data.

6. Download_data.py: Downloads the penguin data and saves it to the local storage.
7. check_data.py: Checks the validity of the data and ensures no corruption during download.
8. data_database.py: Manages the interaction with the local SQLite database (penguins.db), which stores the cleaned and processed data.
9. Penguin-Classification/: This folder contains essential files for the penguin classification model.

10. README.md: Documentation about the project.
11. Prediction/: Contains the files for running the model and making daily predictions.

12. prediction_test.py: This script loads the trained classifier model (penguin_classifier.pkl), fetches new data from the API, and makes a prediction on the species.
Train Test/: This folder contains the scripts for training the classifier model.

13. train_test.py: The main script that handles the training of the Random Forest classifier, saving the trained model as penguin_classifier.pkl.
14. data/: Contains the raw data files used for training and prediction.

penguins.csv: The CSV file containing the original penguin dataset used for model training.
penguins.db: The SQLite database file where the cleaned and processed data is stored.
penguin_classifier.pkl: The saved Random Forest classifier model that is used to make predictions on new penguin data.

requirement.txt: A text file containing the list of Python dependencies required for the project, such as scikit-learn, Flask, and other libraries.
