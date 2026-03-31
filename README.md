## Water Quality Prediction Application 💧
This project is a Streamlit-based web application that predicts the potability of water based on various water quality parameters. It uses machine learning algorithms, particularly the XGBoost Classifier, to determine whether the water is safe for drinking.

---

## Screenshot 📸

![img_alt](https://github.com/vinutmaradur/Data_Science-Water_quality_test_prediction/blob/main/wp%201.png)
![img alt](https://github.com/vinutmaradur/Data_Science-Water_quality_test_prediction/blob/main/wp%202.png)

---

## About Dataset 📊

The water_potability.csv dataset contains information about water samples and their potability status. This dataset can be used to build machine learning models to predict whether water is safe for drinking based on its physical and chemical properties.

**Dataset Description**

The dataset includes 10 columns:

1. pH 🧪:

- A measure of how acidic or basic water is.
- **Range**: 0 to 14
- Drinking water should ideally have a pH between 6.5 and 8.5.
  
2. Hardness 💎:

- Represents the concentration of calcium and magnesium ions in water.
- **Unit**: mg/L
- High levels of hardness can cause scaling in pipes and reduce soap effectiveness.
  
3. Solids 🌊:

- Total dissolved solids (TDS) in water.
- **Unit**: ppm (parts per million)
- Excessive solids can affect taste and health.
  
4. Chloramines 🧼:

- Amount of chloramines present in water.
- **Unit**: ppm
- Chloramines are used for water disinfection but should be within safe levels.
  
5. Sulfate 🧂:

- Concentration of sulfate ions in water.
- **Unit**: mg/L
- High sulfate levels can cause a laxative effect.
  
6. Conductivity ⚡:

- Electrical conductivity of water, indicating the ion concentration.
- **Unit**: µS/cm
- Helps understand the mineral content in water.
  
7. Organic_carbon 🌱:

- Amount of organic carbon in water.
- **Unit**: ppm
- High levels can indicate contamination from organic waste.
  
8. Trihalomethanes 🧴:

- Concentration of trihalomethanes in water.
- **Unit**: µg/L
- Byproduct of chlorination; excessive levels are harmful.
  
9. Turbidity 🌪️:

- Cloudiness of water caused by suspended particles.
- **Unit**: NTU (Nephelometric Turbidity Unit)
- High turbidity can harbor harmful microorganisms.
  
10. Potability  🚰:

- A binary indicator of water safety.
- Values:
   - 0: Not Potable 🛑 (Unsafe for drinking)
   - 1: Potable ✅ (Safe for drinking)
     
# Usage
This dataset is ideal for:

- Building machine learning models for classification problems.
- Analyzing the quality of water based on various features.
- Understanding the impact of water properties on its potability.
  
# Source
The dataset is publicly available and commonly used in data science projects. If this dataset is sourced from a specific platform or research paper, please provide attribution here.

---

## Features 🎯

- **Interactive User Interface**: Users can input water quality parameters and get predictions on water potability.
- **Machine Learning Model**: A trained XGBoost model is used to classify water as potable or non-potable.
- **Dataset Handling**: The app preprocesses the water potability dataset to handle missing values before training the model.

---

## Tech Stack 🔍
- Python 🐍
- Streamlit ☁️
- Pandas 📊
- NumPy 🧮
- Scikit-learn 🤖
- XGBoost 🔮

---

## Installation 🛠️ and Setup ⚙️
  1. Clone the Repository
  ```bash
  git clone https://github.com/your-username/your-repo-name.git  
  cd your-repo-name
  ```
  2. Install Dependencies
   Make sure you have Python 3.8 or higher installed. Run the following command to install the required Python libraries:
   ```bash
       pip install -r requirements.txt
   ```
   Example requirements.txt
   ```bash
     streamlit  
     pandas  
     numpy  
     scikit-learn  
     xgboost
   ```
   3. Prepare the Dataset
    - Place the water_potability.csv dataset in the project root directory.
      
   4. Run the Application
   Start the Streamlit app by running:
      ```bash
       streamlit run app.py  
      ```
   5. Access the Application
   Open your web browser and navigate to http://localhost:8501 to interact with the app.

  ---

 ## Usage 💻
 
1. Launch the app and input the following water parameters:
- pH Value
- Hardness
- Solids (mg/L)
- Chloramines (mg/L)
- Sulfate (mg/L)
- Conductivity (μS/cm)
- Organic Carbon (mg/L)
- Trihalomethanes (μg/L)
- Turbidity (NTU)
2. Click on the "Predict Water Quality" button.
3. The app will display whether the water is Potable or Not Potable based on the input parameters.

---

## File Structure 📂
```bash
  ├── app.py                  # Main application script  
  ├── water_potability.csv    # Dataset (to be added manually)  
  ├── requirements.txt        # Dependency list  
  └── README.md               # Project documentation
 ```

 ---

 ## Contributing 🤝
  
   Contributions are welcome! Feel free to submit a pull request or report issues.

 ---

## License 📄

  This project is licensed under the MIT License.

---

## Acknowledgments 🙌
- Streamlit for providing an excellent framework for building interactive web applications.
- The dataset and machine learning model used for this project.

---

## Check my code 👁️
Below is the link to check my app

  [Project demo](https://waterqualitytestprediction-2025.streamlit.app/) 🚀

---

## Happy Coding! 💻✨

You can modify sections like the GitHub repository link or license if needed. Let me know if you'd like help adding anything else!

 ---

**👨‍💻 Author** </br>
Vinut Maradur </br>
MCA (Data Science) Graduate | Data Analyst | Data Science Enthusiast
