# OptiCrop
OptiCrop is a machine learning-based agricultural recommendation system built with Flask and Scikit-learn. It analyzes soil nutrients (N, P, K) and environmental factors such as temperature, humidity, pH, and rainfall to recommend the most suitable crop, helping farmers make data-driven decisions for improved productivity and sustainability.
 Repository Structure
OptiCrop/
│
├── app.py                     # Main Flask application
├── train_model.py             # Model training script
├── predict.py                 # Prediction logic
├── requirements.txt           # Project dependencies
├── README.md                  # Project documentation
├── LICENSE                    # MIT License
├── .gitignore                 # Git ignored files
├── Procfile                   # Render deployment configuration
├── runtime.txt                # Python runtime version
│
├── dataset/
│   └── Crop_recommendation.csv    # Agricultural dataset
│
├── models/
│   └── crop_model.pkl             # Trained machine learning model
│
├── notebooks/
│   └── Model_Training.ipynb       # ML model development notebook
│
├── templates/
│   ├── index.html                 # Home page
│   ├── result.html                # Prediction result page
│   ├── about.html                 # About project page
│   └── base.html                  # Common layout template (optional)
│
├── static/
│   ├── css/
│   │   └── style.css              # Stylesheets
│   ├── js/
│   │   └── script.js              # JavaScript functions
│   └── images/
│       ├── logo.png
│       ├── banner.jpg
│       ├── home.png
│       └── prediction.png
│
├── screenshots/
│   ├── home-page.png              # Home page screenshot
│   ├── input-form.png             # Input form screenshot
│   └── prediction-result.png      # Prediction result screenshot
│
└── docs/
    ├── Project_Report.pdf         # Final project report
    ├── Presentation.pptx          # Project presentation
    └── Architecture.png           # System architecture diagram
```
