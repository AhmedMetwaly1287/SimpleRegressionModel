<h1>Simple Linear Regression Model</h1>

<p><strong>This project was built for the Business Intelligence & Data Analytics Course for the Faculty of Computers & Artifical Intelligence - Helwan University</strong></p>

<h2>Details</h2>
<h4><strong>Libraries used for this project:</strong></h4>
<ol>
  <li value='1'>Pandas</li>
  <li>Scikit-Learn</li>
</ol>

<h4><strong>Dataset used for this project:</strong></h4>
<ol>
California Housing Prices (Adjusted using ChatGPT to control the number of null rows)
</ol>

<h4><strong>This Project was divided into two phases: </strong></h4>
<ol>
  <li value='1'>Data Pre-processing and Transformation</li>
  <li>Building the Linear Regression Model</li>
</ol>

<h4><strong>1- Data Pre-processing and Transformation</strong></h4>
<p><strong>Pandas was utilized to read the dataset, display information about the columns inside the dataset such as the number of non-null rows and the data type of each column
and then the first 20 rows are displayed, the number of null rows in each column is then displayed then the null rows are being handled by being filled using Mean, Median, Mode for the categorical columns respectively,
It's also important to note that the categorical columns were encoded using One-Hot and Numerical Encoding for easier, more accurate model training</strong></p>

<h4><strong>2- Building the Linear Regression Model</strong></h4>
<p><strong>Scikit-Learn as utilized to then split our data into training set and test set and the data is then scaled to keep the data within a specific range of values, the model is then created and trained and a Scatter Plot is created to demonstrate the best fit line
and the value of different types of error such as the Mean Absolute Error and the Root Mean Squared Error is then calculated </strong></p>

<h4><strong>To-Do List</strong></h4>
<ol>
  <li value='1'>Handle Outliers</li>
  <li>Build the Model using different Regression Algorithms</li>
</ol>
