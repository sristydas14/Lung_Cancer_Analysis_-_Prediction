  <h1>🫁 Lung Cancer Analysis & Prediction</h1>

  <p>This project involves data exploration and prediction of lung cancer likelihood based on survey responses using machine learning. The goal is to identify key patterns and train models to classify whether an individual is likely to have lung cancer.</p>

  <h2>📁 Dataset Overview</h2>
  <ul>
    <li>Filename: <code>survey lung cancer.csv</code></li>
    <li>Rows: 309</li>
    <li>Columns: 16</li>
    <li>Target Column: <code>LUNG_CANCER</code> (Yes/No)</li>
    <li>Features include: Age, Gender, Smoking, Symptoms (e.g., Coughing, Fatigue), Habits (e.g., Alcohol consumption)</li>
  </ul>

  <h2>🧹 Data Cleaning</h2>
  <ul>
    <li>Converted binary numeric values (1/2) to Yes/No for better readability</li>
    <li>Standardized column values (e.g., M/F to Male/Female)</li>
    <li>Removed duplicates</li>
  </ul>

  <h2>📊 Exploratory Data Analysis (EDA)</h2>
  <ul>
    <li>Histogram of Age for lung cancer positive cases</li>
    <li>Gender distribution among patients with lung cancer</li>
    <li>Bar plots comparing symptoms and habits across gender (e.g., Smoking, Alcohol, Anxiety)</li>
  </ul>

  <h2 id="gallery">🖼️ Gallery</h2>

<h3>📌 Positive Cases' Age Distribution</h3>
<img src="https://github.com/user-attachments/assets/f6882150-f486-4162-bca8-2868901d58ee" width="600" height="400">

<h3>📌 Positive Cases' Gender Distribution</h3>
<img src="https://github.com/user-attachments/assets/2d0f9711-c763-4841-844e-a7fc75100a25" width="600" height="400">

<h3>📌 Gender-wise Positive Cases' Reasons</h3>
<img src="https://github.com/user-attachments/assets/d30a0dfa-5e9c-4b6a-9a8c-a0025500ef33" width="600" height="400">

<h3>📌 Gender-wise Positive Cases' Symptoms</h3>
<img src="https://github.com/user-attachments/assets/ba335815-e338-4434-800e-4ad5988ec2b0" width="600" height="400">

<h3>📌 Correlation Heatmap</h3>
<img src="https://github.com/user-attachments/assets/3d0ec8ef-a673-4822-aa55-103b596faf62" width="600" height="400">

<h3>🛠️ Training and Testing Accuracy for Models</h3>

<h3>📌 Performance Evaluation - Lung Cancer Analysis</h3>
<img src="https://github.com/user-attachments/assets/205f8641-71fc-4aee-aa69-6257188de464" width="600" height="400">

<h3>📌 Confusion Matrix on Applied Testing Models</h3>
<img src="https://github.com/user-attachments/assets/37e41397-69be-4e0b-9505-731a09043afe" width="600" height="400">

<h3>📌 ROC - Curve on Applied Testing Models</h3>
<img src="https://github.com/user-attachments/assets/9ddb80f3-21aa-4a25-b276-9099b31985f4" width="600" height="400">

<br>

  <h2>🔬 Correlation Analysis</h2>
  <p>A Pearson correlation heatmap was created to understand feature relationships. Features like Smoking and Yellow Fingers showed stronger correlations with lung cancer incidence.</p>

  <h2>🛠️ Preprocessing</h2>
  <ul>
    <li>Label encoding for target column</li>
    <li>One-hot encoding for Gender</li>
    <li>StandardScaler used for feature normalization</li>
    <li>Train-test split: 80% training, 20% testing</li>
  </ul>

  <h2>🤖 Model Training & Evaluation</h2>
  <h3>Logistic Regression</h3>
  <ul>
    <li>Trained with default settings</li>
    <li>Evaluated using Accuracy, Confusion Matrix, Classification Report</li>
  </ul>

  <h3>Support Vector Machine (SVM)</h3>
  <ul>
    <li>Used C = 100, gamma = 0.002</li>
    <li>Provided accurate classification results on test data</li>
  </ul>

  <h2>✅ Conclusion</h2>
  <ul>
    <li>Thorough visual and statistical analysis was conducted</li>
    <li>Both Logistic Regression and SVM provided good accuracy</li>
    <li>Symptoms like Coughing, Yellow Fingers, Fatigue were significant indicators</li>
  </ul>

  <h2>📌 Future Scope</h2>
  <p>The project can be expanded and improved in several ways:</p>
  <ul>
    <li><strong>Advanced Models:</strong> Implementation of ensemble methods like Random Forest, XGBoost, and Gradient Boosting could improve accuracy.</li>
    <li><strong>Cross-Validation:</strong> Using k-fold cross-validation would make performance metrics more robust.</li>
    <li><strong>Hyperparameter Tuning:</strong> Applying GridSearchCV or RandomizedSearchCV can help find the best model parameters.</li>
    <li><strong>Feature Engineering:</strong> Creating interaction features or combining symptoms might provide better insights.</li>
    <li><strong>Handling Class Imbalance:</strong> Techniques like SMOTE or class weighting could be applied if dataset has skewed class distribution.</li>
    <li><strong>Deep Learning:</strong> With more data, neural networks can be used to capture nonlinear patterns.</li>
    <li><strong>Deployment:</strong> Building a web app using Flask or Streamlit to make real-time predictions.</li>
  </ul>

  <hr>
  <p><strong>Author:</strong> Sristry Rani Das<br>
     <strong>GitHub:</strong> <a href="https://github.com/sristydas14">Sristy Rani Das</a>
  </p>
</body>
</html>
