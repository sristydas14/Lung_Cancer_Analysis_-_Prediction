  <h1>Lung Cancer Analysis & Prediction</h1>

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

  <h2>🖼️ Gallery</h2>
  <p>Below are sample visualizations generated during the EDA phase:</p>
  <ul>
    <li><strong>Age Distribution of Patients:</strong><br>
      <img src="images/age_distribution.png" alt="Age distribution histogram">
    </li>
    <li><strong>Gender vs Smoking:</strong><br>
      <img src="images/gender_vs_smoking.png" alt="Bar chart of gender vs smoking">
    </li>
    <li><strong>Correlation Heatmap:</strong><br>
      <img src="images/heatmap.png" alt="Correlation heatmap">
    </li>
  </ul>

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
  <p><strong>Author:</strong> Your Name Here<br>
     <strong>GitHub:</strong> <a href="https://github.com/yourusername">@yourusername</a>
  </p>
</body>
</html>
