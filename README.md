<!DOCTYPE html>
<html lang="en">
<body>

<h1>📏 Father and Son Height Prediction</h1>

<p>
This project is a <strong>Simple Linear Regression based Machine Learning application</strong>
that predicts a <strong>son’s height</strong> based on the <strong>father’s height</strong>.
The trained model is deployed using <strong>Flask</strong> and presented through a simple web interface.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
Human height inheritance shows a strong linear relationship between parent and child.
This project demonstrates how <strong>statistical learning</strong> and
<strong>machine learning</strong> can be applied to model that relationship.
</p>

<p>
The goal is to:
</p>

<ul>
    <li>Analyze the relationship between father and son height</li>
    <li>Train a Simple Linear Regression model</li>
    <li>Predict son’s height for a given father’s height</li>
    <li>Deploy the model as a web application</li>
</ul>

<hr>

<h2>📊 Dataset Information</h2>

<ul>
    <li><strong>Dataset:</strong> Pearson.csv</li>
    <li><strong>Source:</strong> Pearson’s historical height data</li>
</ul>

<h3>🔍 Features</h3>

<table border="1" cellpadding="6" cellspacing="0">
    <tr>
        <th>Feature</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Father Height</td>
        <td>Height of the father (input variable)</td>
    </tr>
    <tr>
        <td>Son Height</td>
        <td>Height of the son (target variable)</td>
    </tr>
</table>

<hr>

<h2>⚙️ Project Architecture</h2>

<pre>
Father-Son-Height-Prediction/
│
├── app.py                  # Flask application
├── Pearson.csv             # Dataset
├── SLR_Task.ipynb          # Model training & analysis notebook
├── SLR_TASK.pkl            # Trained regression model
├── requirements.txt        # Project dependencies
├── Procfile                # Deployment configuration
│
├── templates/
│   └── index.html          # Web interface
│
└── static/
    └── css/
        └── style.css       # Styling (if enabled)
</pre>

<hr>

<h2>🔁 Machine Learning Workflow</h2>

<h3>1️⃣ Data Analysis</h3>
<ul>
    <li>Dataset loaded using Pandas</li>
    <li>Relationship analyzed between father and son heights</li>
    <li>Visualizations created using Matplotlib</li>
</ul>

<h3>2️⃣ Model Training</h3>
<ul>
    <li>Algorithm Used: <strong>Simple Linear Regression</strong></li>
    <li>Model trained using <code>scikit-learn</code></li>
    <li>Linear relationship learned from historical data</li>
</ul>

<h3>3️⃣ Model Saving</h3>
<ul>
    <li>Trained model serialized using <code>pickle</code></li>
    <li>Saved as <code>SLR_TASK.pkl</code></li>
</ul>

<hr>

<h2>🌐 Model Deployment (Flask)</h2>

<p>
The trained regression model is deployed using Flask.
</p>

<ul>
    <li>User enters father’s height through web form</li>
    <li>Input is converted to NumPy array</li>
    <li>Model predicts the son’s height</li>
    <li>Prediction is displayed on the same page</li>
</ul>

<p>
<strong>Prediction Output:</strong><br>
Predicted Son Height (numeric value)
</p>

<hr>

<h2>🎨 Web Interface</h2>

<ul>
    <li>HTML-based input form</li>
    <li>Bootstrap used for basic styling</li>
    <li>Single input → single output flow</li>
    <li>Beginner-friendly UI</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
    <li>Python</li>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Scikit-learn</li>
    <li>Flask</li>
    <li>HTML & Bootstrap</li>
</ul>

<hr>

<h2>▶️ How to Run the Project</h2>

<h3>1️⃣ Install Dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>

<h3>2️⃣ Run Flask Application</h3>
<pre>
python app.py
</pre>

<h3>3️⃣ Open Browser</h3>
<pre>
http://127.0.0.1:5000/
</pre>

<hr>

<h2>🚀 Key Learnings</h2>

<ul>
    <li>Understanding Simple Linear Regression</li>
    <li>Relationship between dependent and independent variables</li>
    <li>Model serialization using Pickle</li>
    <li>Flask-based ML deployment</li>
    <li>End-to-end ML project workflow</li>
</ul>

<hr>

<h2>📌 Future Enhancements</h2>

<ul>
    <li>Add mother’s height for multivariate regression</li>
    <li>Improve UI with charts</li>
    <li>Deploy on cloud (Heroku / Render)</li>
    <li>Add input validation</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<strong>Bala Venu</strong><br>
Data Scientist & Machine Learning Enthusiast
</p>

</body>
</html>
