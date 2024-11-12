# Data Analysis iPhone Sale Dataset :

<h2>Overview</h2>
<p>This mini project focuses on data analysis of the iPhone Apple dataset using Python. The analysis includes basic transformations and exploratory data analysis (EDA) to derive insights from the dataset. The primary libraries used for this project are <strong>Pandas</strong> for data manipulation and <strong>Matplotlib</strong> for data visualization.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#technologies-used">Technologies Used</a></li>
    <li><a href="#data-transformation-and-analysis">Data Transformation and Analysis</a></li>
    <li><a href="#visualizations">Visualizations</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="#introduction">Introduction</h2>
<p>The iPhone Apple dataset contains various attributes related to different iPhone models, including their prices, discounts, colors, and specifications. The goal of this project is to perform data cleaning, transformation, and analysis to uncover patterns and insights within the dataset.</p>

<h2 id="#dataset">Dataset</h2>
<p>The dataset used in this project includes the following columns:</p>
<ul>
    <li><strong>Product Name</strong>: Name of the product with its specifications.</li>
    <li><strong>Product URL</strong>: Link to buy the product.</li>
    <li><strong>Brand</strong>: Brand of the phone (Apple).</li>
    <li><strong>Sale Price</strong>: Current sale price available for customers.</li>
    <li><strong>Mrp</strong>: Original retail price in the market. </li>
    <li><strong>Discount</strong>: Discount in percentage.</li>
    <li><strong>Number Of Ratings</strong>: Total ratings received.</li>
    <li><strong>Number Of Reviews</strong>: Total reviews received.</li>
    <li><strong>Upc</strong>: Universal product code.</li>
    <li><strong>Star Rating</strong>: Star ratings given to the product.</li>
    <li><strong>Ram</strong>: Storage of the phone.</li>


</ul>
<p>The following dataset is used for the following project. <a href = "apple_products.csv"> Apple_iPhone_Dataset</a></p>

<h2 id="#technologies-used">Technologies Used</h2>
<ul>
    <li><strong>Python 3.x : Programming Language.</strong></li>
    <li><strong>Pandas</strong>: For data manipulation and analysis.</li>
    <li><strong>Matplotlib</strong>: For creating visualizations.</li>
    <li><strong>Jupyter Notebook</strong>: For interactive and computational data analysis.</li>
</ul>

<h2 id="#data-transformation-and-analysis">Data Transformation and Analysis</h2>
<p>In this project, the following transformations and analyses were performed:</p>
<ul>
    <li><strong>Data Loading</strong>: Loaded the dataset using Pandas and inspected its structure.</li>
    <li><strong>Data Cleaning</strong>: Checked for and handled missing values, filled missing values with appropriate values. </li>
    <li><strong>Basic Operations</strong>: 
        <ul>
            <li>Use of basic aggregate functions like count(), min(), max(). </li>
            <li>Grouped data by model names to count the number of occurrences.</li>
            <li>Extracted relevant features such as colors associated with each model using regular expression                    library.</li>
        </ul>
    </li>
    <li><strong>Basic Statistical Analysis</strong>: Analyzed summary statistics for pricing and discount columns,reviews recieved for each model for the customers to decide the most suited phones with their needs. </li>
</ul>

<h2 id="#visualizations">Visualizations</h2>
<p>Visualizations were created to represent key insights from the dataset:</p>
<ul>
    <li><strong>Scatter Plot</strong>: A scatter plot showing the relationship between the price and discount of each iPhone model.</li>
    <li><strong>Bar Charts</strong>: Bar charts depicting the reviews recieved for each model.</li>   
</ul>
<p>The visualizations help in identifying trends and outliers in the data, making it easier to draw conclusions.</p>

<h2 id="#conclusion">Conclusion</h2>
<p>This project provided insights into the iPhone Apple dataset, showcasing how basic data analysis and visualization techniques can be used to understand pricing strategies and discounts across different iPhone models. The findings can be useful for consumers making purchasing decisions and for the company in strategizing their pricing models.</p>

<h2 id="#license">License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE" target="_blank">LICENSE</a> file for details.</p>

</body>
</html>
