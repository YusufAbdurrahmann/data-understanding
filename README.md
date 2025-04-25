<h1>📊 Data Understanding – Learning Notes (By Yusuf Abdurrahman)</h1>
<p><em>"Before you clean it, you need to understand it."</em></p>

<h2>🔍 What I Learned in Data Understanding</h2>
<p>Understanding the structure and characteristics of a dataset is the first step in any data analysis project. Here's what I explored:</p>

<hr>

<h3>1. Dataset Dimensions (<code>df.shape</code>)</h3>
<p>Understand the size of the dataset — the number of rows (records) and columns (features).</p>
<strong>Why it matters:</strong>
<p>It gives a quick overview of the data's scale and helps plan analysis steps accordingly.</p>

<h3>2. Data Types (<code>df.dtypes</code>)</h3>
<p>Identify the type of data in each column, such as integers, floats, or strings.</p>
<strong>Why it matters:</strong>
<p>Knowing data types ensures you apply the right transformations and avoid errors in processing.</p>

<h3>3. Duplicate Records (<code>df.duplicated()</code>)</h3>
<p>Check for repeated rows in the dataset.</p>
<strong>Why it matters:</strong>
<p>Duplicates can distort analysis and should be addressed to maintain data quality.</p>

<h3>4. Missing Values (<code>df.isnull().sum()</code>)</h3>
<p>Detect how many missing (null) values are present in each column.</p>
<strong>Why it matters:</strong>
<p>Identifying missing values helps prepare for data cleaning strategies such as imputation or removal.</p>

<h3>5. Data Summary Info (<code>df.info()</code>)</h3>
<p>Get a concise summary including the number of non-null entries, data types, and memory usage.</p>
<strong>Why it matters:</strong>
<p>Provides an at-a-glance health check of your dataset and helps spot inconsistencies.</p>

<h3>6. Statistical Summary (<code>df.describe()</code>)</h3>
<p>View descriptive statistics like mean, median, standard deviation, min, and max for numerical columns.</p>
<strong>Why it matters:</strong>
<p>Helps understand the data distribution, variability, and potential outliers.</p>

<hr>

<h2>📌 Key Takeaways</h2>
<ul>
  <li>Exploring your data is a crucial step before cleaning or modeling.</li>
  <li>It helps you detect potential problems early and make better-informed decisions.</li>
  <li>Data understanding builds the foundation for every successful data science project.</li>
</ul>
