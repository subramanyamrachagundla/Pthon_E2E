<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Power BI End-to-End Project</title>
</head>
<body>

<h1>📊 Power BI End-to-End Project</h1>

<p>
  This repository showcases a complete end-to-end Power BI project — from data collection and transformation to dashboard creation and publishing. It is intended for data analysts, business intelligence developers, and enthusiasts looking to understand how to build a full Power BI solution.
</p>

<hr>

<h2>🗂️ Table of Contents</h2>
<ul>
  <li><a href="#project-overview">Project Overview</a></li>
  <li><a href="#prerequisites">Prerequisites</a></li>
  <li><a href="#dataset-information">Dataset Information</a></li>
  <li><a href="#data-preparation">Data Preparation (Power Query)</a></li>
  <li><a href="#data-modeling">Data Modeling</a></li>
  <li><a href="#report-building">Report Building</a></li>
  <li><a href="#publishing">Publishing to Power BI Service</a></li>
  <li><a href="#refresh-scheduling">Refresh Scheduling</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><a href="#conclusion">Conclusion</a></li>
</ul>

<hr>

<h2 id="project-overview">📌 Project Overview</h2>
<p>
  This project demonstrates a business intelligence dashboard that provides actionable insights using Power BI. The project involves:
</p>
<ul>
  <li>Loading data from multiple sources</li>
  <li>Cleaning and transforming data using Power Query</li>
  <li>Building data models and DAX measures</li>
  <li>Designing interactive reports and dashboards</li>
  <li>Publishing to Power BI Service with auto-refresh</li>
</ul>

<hr>

<h2 id="prerequisites">⚙️ Prerequisites</h2>
<ul>
  <li>Power BI Desktop (latest version)</li>
  <li>Basic knowledge of Power Query and DAX</li>
  <li>Microsoft Power BI Service account (for publishing)</li>
</ul>

<hr>

<h2 id="dataset-information">📁 Dataset Information</h2>
<p>
  The dataset used in this project includes:
</p>
<ul>
  <li>Sales Data (CSV format)</li>
  <li>Customer Demographics (Excel format)</li>
  <li>Product Master (Excel format)</li>
</ul>
<p>
  All datasets are stored inside the <code>/data</code> folder.
</p>

<hr>

<h2 id="data-preparation">🧹 Data Preparation (Power Query)</h2>
<p>
  Power Query Editor is used to:
</p>
<ul>
  <li>Remove unnecessary columns</li>
  <li>Fix data types</li>
  <li>Handle missing/null values</li>
  <li>Merge and append queries</li>
  <li>Create calendar/date table</li>
</ul>

<hr>

<h2 id="data-modeling">🧠 Data Modeling</h2>
<p>
  Star schema is followed with proper relationships between fact and dimension tables. Key concepts:
</p>
<ul>
  <li>Fact Table: Sales</li>
  <li>Dimension Tables: Customers, Products, Date</li>
  <li>DAX Measures: Total Sales, Profit Margin, YoY Growth</li>
</ul>

<hr>

<h2 id="report-building">📈 Report Building</h2>
<p>
  Interactive visuals are created using Power BI Desktop including:
</p>
<ul>
  <li>Bar/Column charts</li>
  <li>Pie charts</li>
  <li>Line charts</li>
  <li>Cards and KPIs</li>
  <li>Slicers and filters</li>
  <li>Drillthrough and tooltips</li>
</ul>

<hr>

<h2 id="publishing">☁️ Publishing to Power BI Service</h2>
<p>
  Steps:
</p>
<ol>
  <li>Save your PBIX file</li>
  <li>Click <strong>Publish</strong> → Select Workspace</li>
  <li>Verify report and dataset on Power BI Service</li>
</ol>

<hr>

<h2 id="refresh-scheduling">⏰ Refresh Scheduling</h2>
<p>
  Setup data refresh schedule:
</p>
<ul>
  <li>Go to Power BI Service → Dataset settings</li>
  <li>Configure credentials and gateway (if needed)</li>
  <li>Set daily/weekly refresh time</li>
</ul>

<hr>

<h2 id="screenshots">🖼️ Screenshots</h2>
<p>Add screenshots of your Power BI reports below:</p>
<ul>
  <li><img src="images/dashboard1.png" alt="Dashboard Screenshot 1" width="600"></li>
  <li><img src="images/dashboard2.png" alt="Dashboard Screenshot 2" width="600"></li>
</ul>

<hr>

<h2 id="conclusion">✅ Conclusion</h2>
<p>
  This Power BI project demonstrates a complete data journey — from raw data to published dashboard. It showcases data wrangling, modeling, and visualization best practices. Feel free to fork or adapt this project for your own learning or business use case.
</p>

<hr>

<h3>📬 Contact</h3>
<p>
  Created by [Your Name] — feel free to connect!
</p>

</body>
</html>

