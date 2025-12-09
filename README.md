# Predict Candidate Fit Score
# Analyzation-of-candidate-profilies-
<span style="font-size:50px; font-weight:700;"> Candidate Fit Score

<span style="font-size:35px; font-weight:400;"> Candidate–Job Matching System</span></span>

<h1 align="center"> Candidate Fit Score</h1>
<p align="center"><strong>AI Candidate–Job Predictor</strong></p>

<p>
A lightweight machine learning system that analyzes a candidate’s profile and a job description to generate a <strong>Fit Score (0–100%)</strong>.  
Useful for HR teams, recruiting platforms, resume screening tools, and automation workflows.
</p>

<hr>

<h2>✨ Features</h2>
<ul>
  <li> Intelligent text processing for candidate & job descriptions</li>
  <li> TF-IDF feature extraction</li>
  <li> Machine learning model using scikit-learn</li>
  <li> Generates match scores between 0 and 100</li>
  <li> Simple, clean, and extendable codebase</li>
  <li> Works on macOS, Windows, and Linux</li>
</ul>

<hr>

<h2>🛠 Technologies Used</h2>
<ul>
  <li><strong>Python</strong></li>
  <li><strong>scikit-learn</strong></li>
  <li><strong>Pandas</strong></li>
  <li><strong>NumPy</strong></li>
  <li><strong>joblib</strong></li>
  <li><strong>TF-IDF Vectorizer</strong></li>
</ul>

<hr>

<h2>📁 Project Structure</h2>

<pre>
candidate_fit_project/
│── main.py                # Training + prediction logic
│── sample_data.csv        # Training dataset
│── model.pkl              # Saved ML model
│── vectorizer.pkl         # Saved TF-IDF vectorizer
│── README.md
</pre>

<hr>

<h2>🚀 How It Works</h2>

<h3>1️⃣ Data Processing</h3>
<p>Loads and cleans candidate & job description text.</p>

<h3>2️⃣ Feature Engineering</h3>
<p>Converts raw text into TF-IDF numerical vectors.</p>

<h3>3️⃣ Model Training</h3>
<p>Machine learning model learns relationships from example scores.</p>

<h3>4️⃣ Prediction</h3>
<p>The <code>predict()</code> function returns a score from 0 to 100.</p>

<hr>

<h2>💻 Setup & Run Instructions (macOS / Windows / Linux)</h2>

<h3>1. Extract Project</h3>
<p>Unzip the downloaded folder.</p>

<h3>2. Open in VS Code</h3>
<p>File → Open Folder → <em>candidate_fit_project</em></p>

<h3>3. Create Virtual Environment</h3>

<pre>
python3 -m venv venv
source venv/bin/activate    # macOS/Linux
</pre>

<h3>4. Install Dependencies</h3>

<pre>
pip install pandas scikit-learn joblib
</pre>

<h3>5. Train the Model</h3>

<pre>
python3 main.py
</pre>

<p><strong>Expected Output:</strong> <code>Model trained.</code></p>

<h3>6. Run a Prediction</h3>

<pre>



