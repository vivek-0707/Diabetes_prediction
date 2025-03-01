# Diabetes Prediction System

## Overview
This project demonstrates the development of a **Diabetes Prediction System** using machine learning techniques. The system follows an end-to-end process from data preprocessing to model deployment, providing a practical and user-friendly solution for predicting whether a person has diabetes based on specific health parameters.

## Features
- **Data Preprocessing**: Cleaned and processed the dataset to handle missing values, normalize features, and prepare the data for machine learning.
- **Model Development**: Trained a **Random Forest Classifier** to achieve accurate predictions. The model was evaluated and tuned for optimal performance.
- **Predictive System**: Built a robust predictive system that classifies whether a person is diabetic or non-diabetic based on the input features.
- **Pickle Integration**: Saved the trained model as a pickle file for efficient loading and deployment.
- **Web App**: Designed a **Streamlit-based web interface** to make the prediction system user-friendly. Users can input their health parameters and view predictions instantly.
- **Interactive UI**: Developed a clean and intuitive user interface for seamless interaction, ensuring accessibility for users with minimal technical expertise.

## Technologies Used
- **Machine Learning**: Scikit-learn
- **Web Framework**: Streamlit
- **Data Handling**: Pandas, NumPy
- **Model Deployment**: Pickle
- **Visualization**: Matplotlib, Seaborn (if applicable)

## Installation
Follow these steps to set up and run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage
- Open the Streamlit web app in your browser.
- Enter the required health parameters.
- Click the **Predict** button to get the diabetes prediction result.

## Model Training
If you wish to retrain the model:
1. Run the `train_model.py` script to preprocess data and train the model.
   ```bash
   python train_model.py
   ```
2. The trained model will be saved as a pickle file (`model.pkl`).

## Contributing
Contributions are welcome! Feel free to submit pull requests or report issues.

## License
This project is open-source and available under the MIT License.

---

Developed with ❤️ using Python and Machine Learning.
