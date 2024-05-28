<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laptop Price Prediction Project</title>
</head>
<body>
    <h1>Laptop Price Prediction Project</h1>

    <p>This project aims to predict laptop prices based on various features such as hardware specifications, brand, operating system, etc. The dataset used for this project is <code>laptop_data.csv</code>.</p>

    <h2>About the Dataset</h2>

    <p>The dataset contains information about various laptops including:</p>
    <ul>
        <li>Company</li>
        <li>Product Type</li>
        <li>Ram</li>
        <li>Weight</li>
        <li>Screen Resolution</li>
        <li>CPU</li>
        <li>GPU</li>
        <li>Operating System</li>
        <li>Price</li>
    </ul>

    <h2>Steps Taken</h2>

    <h3>Data Preprocessing</h3>
    <ul>
        <li>Data Cleaning: Removed unnecessary columns (<code>Unnamed: 0</code>).</li>
        <li>Data Transformation: Converted RAM and Weight columns to appropriate data types.</li>
        <li>Feature Engineering: Extracted useful features from existing columns (e.g., Touchscreen, IPS, etc.).</li>
        <li>Resolved inconsistencies and formatted data for analysis.</li>
    </ul>

    <h3>Exploratory Data Analysis (EDA)</h3>
    <ul>
        <li>Explored various relationships between features and the target variable (Price).</li>
        <li>Visualized distributions, correlations, and trends in the data.</li>
        <li>Utilized libraries such as Pandas, Matplotlib, Seaborn for analysis and visualization.</li>
    </ul>

    <h3>Model Building</h3>
    <ul>
        <li>Utilized various regression algorithms for price prediction:</li>
        <li>Linear Regression</li>
        <li>Ridge Regression</li>
        <li>Lasso Regression</li>
        <li>Decision Tree</li>
        <li>Support Vector Machine (SVM)</li>
        <li>Random Forest</li>
        <li>ExtraTrees</li>
        <li>AdaBoost</li>
        <li>Gradient Boost</li>
        <li>XGBoost</li>
        <li>Stacking</li>
        <li>Voting Regressor</li>
    </ul>

    <h2>Getting Started</h2>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Install the required dependencies listed in <code>requirements.txt</code>.</li>
        <li>Run the Jupyter notebook <code>laptop_price_prediction.ipynb</code> to explore the analysis and models.</li>
    </ol>

    <h2>Conclusion</h2>
    <p>Through this project, we were able to develop machine learning models that predict laptop prices with reasonable accuracy. The best-performing model can be used for real-world applications such as pricing optimization, market analysis, and budget planning.</p>

</body>
</html>
