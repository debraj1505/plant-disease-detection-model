🌱 Plant Disease Prediction Model – Project Update 🚀

I'm excited to share my latest machine learning project focused on early detection of plant diseases — a key step toward sustainable agriculture and food security.

📌 Problem Statement

Plant diseases, especially fungal infections, lead to major crop losses worldwide. These outbreaks are often driven by environmental conditions such as high humidity, high temperature, and rainfall.

🎯 Goal: Predict whether a plant is healthy or diseased based on real-time environmental data — enabling early intervention and improved yield.

🧠 Solution Overview

I developed a Decision Tree Classifier trained on a synthetic dataset of 10,000 samples simulating diverse environmental scenarios.

🚀 Getting Started

Follow these steps to set up the project, train the model, and launch the Streamlit app:

1. Clone the Repository
 
       git clone https://github.com/debraj1505/plant-disease-detection-model.git

2. Create a Virtual Environment
   
# Create environment with Python 3.12

      python -m venv myenv


On Windows:

#Activate the environmwnt

     myenv\Scripts\activate
    
On macOS/Linux:


    source myenv/bin/activate
    
You’ll know it’s activated when your prompt looks like this:


    (myenv) C:\YourPath>
    
3. Install Required Dependencies

       pip install -r requirements.txt
   
requirements.txt should include:

streamlit

scikit-learn

pandas

numpy

matplotlib

joblib

Pillow

4. Train the Model (Optional)

Run the training script to train the model and export plant_disease_detection_model.pkl: Or, open and run the notebook:

    jupyter notebook plant disease prediction.ipynb
    
5. Run the Streamlit App
   
       streamlit run app.py
   
This will open the app in your web browser.

🔍 Features Used

temperature (°C) 🌡️

humidity (%) 💧

rainfall (mm) 🌧️

soil_pH 🧪

🎯 Target

disease_present:

0 = Healthy

1 = Diseased

⚙️ Tech Stack

Python

Scikit-learn (DecisionTreeClassifier)

Pandas, NumPy, Matplotlib

Jupyter Notebook for experimentation

Streamlit for interactive web UI

🚀 Deployment

To make the model accessible to users and farmers, I built a Streamlit web application and deployed it using Streamlit Cloud.

🔧 Deployment Stack:

Streamlit Cloud (for hosting the web app)

GitHub (code repository & version control)

requirements.txt to manage Python dependencies

Model serialized using pickle for efficient loading

🌐 Live App: https://plant-disease-detection-model-jzpe4z5pmtk3oc2wdfdkej.streamlit.app/

🧪 Troubleshooting
If streamlit is not recognized, reactivate your environment.

If plant_disease_detection_model.pkl is missing, ensure train_model.py ran successfully.

Confirm all libraries from requirements.txt are installed.


🌾 Applications

🌱 Smart farming platforms

⚠️ Weather-based plant disease alert systems

📊 Precision agriculture dashboards
