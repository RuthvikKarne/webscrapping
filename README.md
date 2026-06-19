<div align="center">
  <h1>🛒 Amazon Laptop Web Scraping Project</h1>
  <p><i>A data extraction and cleaning pipeline using the STAR Method</i></p>
</div>

<hr>

<h2>🌟 Overview</h2>
<p>
  This repository contains a complete workflow for scraping, extracting, and cleaning laptop data from Amazon. 
  The documentation below follows the <b>STAR Method (Situation, Task, Action, Result)</b> to explain the project's lifecycle.
</p>

<br>

<h2>Situation</h2>
<p>
  In the fast-paced electronics market, having up-to-date information on pricing, specifications, and customer reviews is critical for market analysis and consumer decision-making. There was a need to acquire a comprehensive dataset of laptops currently listed on Amazon to perform competitive analysis and pricing trend evaluations.
</p>

<h2>Task</h2>
<p>
  The objective was to build an automated web scraping pipeline capable of:
  <ul>
    <li>Navigating Amazon's laptop search results.</li>
    <li>Extracting key product details such as title, price, ratings, and specifications.</li>
    <li>Storing the raw extracted data into a structured format.</li>
    <li>Cleaning and preprocessing the raw data to remove inconsistencies, handle missing values, and prepare it for analysis.</li>
  </ul>
</p>

<h2>Action</h2>
<p>
  To achieve this, the following steps were implemented in this repository:
  <ol>
    <li><b>Web Scraping:</b> Developed the <code>amazonwebscrap.ipynb</code> Jupyter Notebook to programmatically request and parse HTML content from Amazon.</li>
    <li><b>Raw Data Collection:</b> Successfully saved the unrefined extracted information into <code>amazon_laptop_raw.csv</code>.</li>
    <li><b>Data Cleaning:</b> Added data transformation steps within the notebook to standardize price formats, clean text fields, and filter out invalid rows.</li>
    <li><b>Final Output:</b> Exported the refined dataset to <code>amazon_laptop_cleaned.csv</code>, ensuring high data quality.</li>
  </ol>
</p>

<h2>Result</h2>
<p>
  The project successfully produced a high-quality, structured dataset (<code>amazon_laptop_cleaned.csv</code>) ready for exploratory data analysis (EDA) and machine learning modeling. The automated script allows for reproducible data collection, significantly reducing the manual effort required for market research.
</p>

<br>
<hr>

<h2>📂 Repository Structure</h2>
<table border="1" cellpadding="10" cellspacing="0" width="100%">
  <thead>
    <tr>
      <th>File/Folder Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code><b>amazonwebscrap.ipynb</b></code></td>
      <td>The main Jupyter Notebook containing the web scraping logic and data cleaning pipeline.</td>
    </tr>
    <tr>
      <td><code><b>amazon_laptop_raw.csv</b></code></td>
      <td>The initial raw data extracted directly from Amazon web pages.</td>
    </tr>
    <tr>
      <td><code><b>amazon_laptop_cleaned.csv</b></code></td>
      <td>The final processed dataset, formatted and ready for analysis.</td>
    </tr>
  </tbody>
</table>

<br>

<h2>🚀 Getting Started</h2>
<p>To run this project locally:</p>
<pre><code># Clone the repository
git clone &lt;repository_url&gt;

# Navigate to the project directory
cd webscrapping

# Open the Jupyter Notebook
jupyter notebook amazonwebscrap.ipynb
</code></pre>
