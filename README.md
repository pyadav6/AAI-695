<h1>Predicting Mental Health Medication Usage and Demographic Characteristics</h1>
<h3>Overview</h3>
This project explores the intersection of mental health care and demographic disparities by building a multi-output machine learning model with two primary objectives:<br>
<ol>
  <li><b>Predicting Medication Usage:</b> Classify individuals into low, medium, or high medication usage categories to identify potential gaps in healthcare delivery.</li>
  <li><b>Predicting Demographic Group and Subgroup:</b> Predict the demographic group (e.g., age, gender) and subgroup (e.g., age range, race, geographic location) an individual likely belongs to, based on their medication usage patterns and associated health statistics.
  The project provides insights into patterns of mental health care accessibility and usage, helping guide public health policies and improve equity in mental health outcomes.</li>
</ol>

<h3>Technologies Used</h3>
<h4>Tech Stack</h4>
<ol>
  <li> Python (Core programming language) </li>
  <li> NumPy, Pandas (Data processing & analysis) </li>
  <li> scikit-learn, TensorFlow, Keras (ML model development) </li>
  <li> Matplotlib, Seaborn (Data visualization) </li>
</ol>

<h4>Machine Learning Models:</h4>
<ul>
  <li>Hybrid Neural Network (HNN)</li>
  <li>Gradient Boosting</li>
  <li>Random Forest</li>
</ul>
<h4>Metrics:</h4> Precision, Recall, F1-Score, Accuracy

<h3>Applications</h3>
This project contributes to research and policy-making by:
<ul>
  <li>Identifying underserved populations and potential gaps in mental health care.</li>
  <li>Informing targeted mental health interventions and resource allocation.</li>
  <li>Providing a framework for analyzing mental health care usage patterns across diverse demographics.</li>
</ul>

<h3>Key Insights</h3>
<h4>Stage 1: Usage Category Prediction</h4>
All three models (HNN, Gradient Boosting, Random Forest) achieved perfect scores in precision, recall, F1-score, and accuracy (1.00).<br>
<b>Conclusion:</b> Medication usage classification is robust across all models.

<h4>Stage 2: Group Prediction</h4>
The HNN model outperformed Gradient Boosting and Random Forest, with a higher F1-score (0.62) and accuracy (0.86).<br>
<b>Conclusion:</b> HNN is the most effective model for predicting demographic groups based on medication usage.

<h4>Stage 3: Subgroup Prediction</h4>
All models performed similarly, with precision, recall, and F1-scores around 0.82-0.84 and accuracy of 81%-82%.<br>
<b>Conclusion:</b> Subgroup prediction is consistent and reliable across all models.<br>
<br>
This project offers actionable insights to improve mental health care access and equity across demographic groups.<br><br>
<b>Link to dataset used:</b> <a href="https://catalog.data.gov/dataset/mental-health-care-in-the-last-4-weeks">https://catalog.data.gov/dataset/mental-health-care-in-the-last-4-weeks</a>
