<h1>🛍️ Nykaa Product Web Scraping & EDA Project</h1>

<h2>🔍 Overview</h2>
<p>
This project involves scraping product data from <strong>Nykaa</strong> and performing 
<strong>Exploratory Data Analysis (EDA)</strong> to uncover insights across 
Beauty, Baby, and Health product categories. The dataset was cleaned, structured, and analyzed 
to understand pricing patterns, stock availability, customer engagement, and category-level trends.
</p>

<hr>

<h2>🎯 Project Objectives</h2>
<ul>
  <li>Scrape product data from Nykaa and build a structured dataset</li>
  <li>Clean and preprocess raw data for accurate analysis</li>
  <li>Perform EDA to identify pricing, demand, and customer engagement patterns</li>
  <li>Generate visual insights for decision-making and trend understanding</li>
</ul>

<hr>

<h2>🛠️ Web Scraping Process</h2>
<ol>
  <li>A program sends an HTTP request to the website server</li>
  <li>Server returns the HTML response</li>
  <li>HTML is parsed using <strong>BeautifulSoup</strong></li>
  <li>Relevant tags and elements are located</li>
  <li>Extracted data is saved into a CSV file</li>
</ol>

<hr>

<h2>📊 Summary of the Data</h2>
<ul>
  <li><strong>Total Products:</strong> 3,400+ items</li>
  <li><strong>Categories Covered:</strong> Beauty, Baby, Health</li>
  <li><strong>Key Columns:</strong> Product_Name, Original_Price, Final_Price, Offer_Percentage, Reviews, Tags, Sizes, Stock, Category</li>
</ul>

<hr>

<h2>🧹 Data Cleaning Steps</h2>
<ul>
  <li>Removed symbols like ₹, %, and formatting text</li>
  <li>Converted price and percentage columns to numeric values</li>
  <li>Added a new <strong>Category</strong> column</li>
  <li>Filled missing values:
    <ul>
      <li>Reviews → 0</li>
      <li>Offer_Percentage → 0</li>
      <li>Sizes → 1</li>
      <li>Tags → "Unknown"</li>
    </ul>
  </li>
  <li>Ensured consistent datatypes across columns</li>
</ul>

<hr>

<h2>📂 Data Manipulation Steps</h2>
<ul>
  <li>Merged Beauty, Baby, and Health datasets into one</li>
  <li>Created grouped summary tables using aggregation</li>
  <li>Identified top/bottom products by:
    <ul>
      <li>Reviews</li>
      <li>Discounts</li>
      <li>Prices</li>
    </ul>
  </li>
  <li>Filtered:
    <ul>
      <li>Top 10 In-Stock products by reviews</li>
      <li>Top 10 Out-of-Stock products by reviews</li>
      <li>Highest-priced products per category</li>
    </ul>
  </li>
</ul>

<hr>

<h2>📊 Univariate Analysis</h2>
<ul>
  <li><strong>Category Distribution:</strong> Beauty has the highest (~1700 products)</li>
  <li><strong>Stock Status:</strong> 91.9% In Stock, 8.1% Out of Stock</li>
  <li><strong>Price Distribution:</strong> Most products range between 0–5,000 with a right-skewed distribution</li>
</ul>

<hr>

<h2>📈 Bivariate Analysis</h2>
<ul>
  <li><strong>Average Final Price by Category:</strong>
    <ul>
      <li>Baby → Lowest (~600)</li>
      <li>Health → Mid (~2000)</li>
      <li>Beauty → Highest (~3100)</li>
    </ul>
  </li>
  <li><strong>Average Reviews by Category:</strong>
    <ul>
      <li>Baby → Highest engagement</li>
      <li>Beauty → Moderate</li>
      <li>Health → Lowest</li>
    </ul>
  </li>
  <li><strong>Offer % vs Final Price:</strong> Negative correlation — higher discounts rarely apply to high-priced items</li>
</ul>

<hr>

<h2>✅ Conclusion</h2>
<ul>
  <li>Beauty category dominates in product count</li>
  <li>Discounts significantly reduce final prices</li>
  <li>Demand varies by category and stock levels</li>
  <li>High-review products align with trustworthy brands</li>
  <li>Pricing and stock strategies strongly influence customer behavior</li>
</ul>

<hr>

<h2>💡 Experience & Challenges</h2>

<h3>Experience</h3>
<ul>
  <li>Hands-on web scraping using BeautifulSoup and Requests</li>
  <li>Real-world data cleaning and preprocessing</li>
  <li>Performed univariate, bivariate, and multivariate analysis</li>
  <li>Visualized insights using Matplotlib and Seaborn</li>
</ul>

<h3>Challenges</h3>
<ul>
  <li>Dynamic content loading via JavaScript</li>
  <li>Handling missing and inconsistent data</li>
  <li>Selecting effective visualizations for insights</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>
<p>
<strong>Teemara Sai</strong><br>
💡 Interested in Python, Web Scraping & Data Analysis
</p>
