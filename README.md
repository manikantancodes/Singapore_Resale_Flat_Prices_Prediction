# Singapore Resale Flat Prices Prediction


The project will involve the following tasks:

1. **Data Collection and Preprocessing**: 
    - Collect a dataset of resale flat transactions from the Singapore Housing and Development Board (HDB) for the years 1990 to Till Date.
    - Preprocess the data to clean and structure it for machine learning.

2. **Feature Engineering**:
    - Extract relevant features from the dataset, including town, flat type, storey range, floor area, flat model, and lease commence date.
    - Create any additional features that may enhance prediction accuracy.

3. **Model Selection and Training**:
    - Choose an appropriate machine learning model for regression (e.g., linear regression, decision trees, or random forests).
    - Train the model on the historical data, using a portion of the dataset for training.

4. **Model Evaluation**:
    - Evaluate the model's predictive performance using regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

5. **Streamlit Web Application**:
    - Develop a user-friendly web application using Streamlit that allows users to input details of a flat (town, flat type, storey range, etc.).
    - Utilize the trained machine learning model to predict the resale price based on user inputs.

6. **Deployment on Render**:
    - Deploy the Streamlit application on the Render platform to make it accessible to users over the internet.

7. **Testing and Validation**:
    - Thoroughly test the deployed application to ensure it functions correctly and provides accurate predictions.





## Setup Instructions
To set up this project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/singapore-flat-resale-price-prediction.git
    cd singapore-flat-resale-price-prediction
    ```

2. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Built the model**:
     ```sh
    singapore_model.ipynb
     ```

5. **Run the Streamlit application**:
    ```sh
    streamlit run app.py
    ```

## Files
- `app.py`: The main application file for the Streamlit app.
- `singapore_model.py`: Contains the code for building and training the machine learning model.
- `requirements.txt`: Lists the required Python packages.
- `README.md`: Project overview and setup instructions.

## License
This project is licensed under the MIT License.


