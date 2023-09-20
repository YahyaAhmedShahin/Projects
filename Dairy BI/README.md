<h1 align="center">Dairy Sales Dataset Analysis</h1>

###

<h2 align="left">Tools</h2>

###

<p align="left">➼ Power BI: <br>Power Query <br>Dax</p>

###

<h2 align="left">Dataset</h2>

###

<p align="left">Dairy Goods Sales Dataset<br><br>➼ Link<br>https://www.kaggle.com/datasets/suraj520/dairy-goods-sales-dataset</p>

###

<p align="left"></p>

###

<h2 align="left">Project Components</h2>

###

<h4 align="left">➼ Fact Table: Dairy Sales<br>➼ Dimension Tables: (Geo, Product,  & Date).<br>➼ Snowflake: Product Inventory</h4>

###

<h2 align="left">Project Applied Steps</h2>

###

<h4 align="left">➼ Power Query Steps</h4>

###

<p align="left">‣ Duplicate Fact Table (Dairy Sales) three times to create dimension and snowflake tables.<br>‣ Rename duplicated version to Geo, Product, and Product inventory.<br>‣ Use the Choose Columns built in tool to choose related columns for each dimension table ex: Product ID for Product Dimension table.<br>‣  Remove Duplicates<br>‣ If needed: Create Index columns as surrogate key for each table.<br>‣ Create your Date dimension table using M language in a blank query editor.</p>

###

<h4 align="left">➼ Power Bi Steps</h4>

###

<p align="left">★ Design a Star Schema<br> Using Unique identifiers.<br><br>‣ Create Many to one relationships between all of the dimension tables (Geo, Product & Date to the fact table (Dairy Sales)<br>‣ Create many to one relationship between the snowflake table (Product Inventory) and the dimension table (Product).</p>

###

<h4 align="left">➼ Dax</h4>

###

<p align="left">Create Measures:<br>‣ Total Sales<br>‣ Total Orders<br>‣ Inventory Balance<br>‣ Closing Inventory<br>‣ Total Cows<br>‣ Total Production<br>‣ Cow Productivity<br><br>Using:<br>‣ SUM, CALCULATE, LASTNONBLANK, COUNT, DIVIDE functions</p>

###

<h4 align="left">➼ Adding Visuals</h4>

###