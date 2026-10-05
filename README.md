<div align="center">

  <h1>🛍️ Retail Sales & ROI Analytics Dashboard</h1>
  <p><b>An End-to-End Enterprise Power BI Dashboard featuring Page Navigation, Advanced M-Code ETL, Product Drill-Downs, and Retail ROI Performance Analysis.</b></p>

  <!-- Clean Tech Stack Badge Bar -->
  <p align="center">
    <code>🟡 Power BI</code> &bull; 
    <code>🔵 Advanced M-Code & Power Query</code> &bull; 
    <code>🟢 Dynamic DAX & ROI</code> &bull; 
    <code>🟣 Page Navigation & UI/UX</code> &bull; 
    <code>🛒 Retail Analytics</code>
  </p>

</div>

<hr />
<br />

<h2>📌 Project Overview</h2>
<p>
  This project delivers an interactive <b>Retail Sales & ROI Performance Analytics Solution</b> built in Power BI. It is tailored for retail managers and enterprise strategists to analyze revenue growth, track return on investment (ROI), drill down into specific product categories (e.g., Electronics & Laptops), and navigate seamlessly across detailed reporting pages.
</p>
<p>
  <b>Business Objective:</b> Enable executives to identify high-margin product categories, optimize promotional pricing, evaluate year-over-year sales metrics, and inspect granular invoice-level transactions.
</p>

<br />

<h2>📊 Executive Dashboard Preview</h2>
<p>The main executive overview interface equipped with dynamic page navigation, top-level KPIs, and category slicers:</p>

<div align="center">
  <img src="https://i.postimg.cc/1zDJwgLL/dashbwrd.png" alt="Retail Sales Executive Dashboard" width="100%" />
</div>

<br />
<hr />
<br />

<h2>🔑 Key Performance Indicators (KPIs)</h2>
<ul>
  <li><b>Total Retail Sales:</b> Overall financial revenue generated across all store categories.</li>
  <li><b>Net Profit & ROI %:</b> Net margin calculations and Return on Investment ratios evaluating category profitability.</li>
  <li><b>Total Quantity & Orders:</b> Total units sold and order volumes fulfilled.</li>
  <li><b>Category Growth & YoY Trends:</b> Time intelligence metrics tracking performance variations across fiscal years (e.g., 2022).</li>
</ul>

<br />
<hr />
<br />

<h2>🛠️ Analytics Architecture & Technical Stages</h2>

<h3>Stage 1: Advanced Power Query ETL & M-Code Customization</h3>
<p>
  Data transformation was executed in <b>Power Query</b>, leveraging the <b>Advanced Editor (M-Code)</b> to handle complex data type conversions, custom conditional column creations, query merging, and automated data cleaning pipelines.
</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Power Query Transformation Steps</h4>
        <img src="https://i.postimg.cc/Zq6Vp912/bawr-kwyry.png" width="95%" alt="Power Query Editor" />
      </td>
      <td width="50%" align="center" valign="top">
        <h4>Advanced Editor M-Code Logic</h4>
        <img src="https://i.postimg.cc/bv13kGK5/adfansd-adybtwr.png" width="95%" alt="Advanced Editor M-Code" />
      </td>
    </tr>
  </table>
</div>

<br />

<h3>Stage 2: DAX Measures & Financial ROI Calculations</h3>
<p>Constructed a robust measure hierarchy for key financial indicators:</p>
<ul>
  <li><code>Total Revenue</code> = <code>SUM(Sales[SalesAmount])</code></li>
  <li><code>Net Profit</code> = <code>SUM(Sales[SalesAmount]) - SUM(Sales[TotalCost])</code></li>
  <li><code>ROI %</code> = <code>DIVIDE([Net Profit], SUM(Sales[TotalCost]), 0)</code></li>
</ul>

<br />
<hr />
<br />

<h2>🎯 Detailed Navigation & Multi-Category Slicing</h2>

<h3>1. Year-Based Performance Analysis (2022 Focus)</h3>
<p>Evaluating annual sales metrics and isolating electronics demand during fiscal year 2022:</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Fiscal Year 2022 Overview</h4>
        <img src="https://i.postimg.cc/s25w7Bkz/mbyʿat-2022.png" width="95%" alt="Sales 2022 Overview" />
        <p align="left"><small>Slices entire report metrics specifically for fiscal year 2022 performance.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>Electronics Category Slicer (2022)</h4>
        <img src="https://i.postimg.cc/Bv2MH8d7/2022-alktrwnyks.png" width="95%" alt="Electronics 2022 Analysis" />
        <p align="left"><small>Deep-dive into Electronics segment revenue drivers during 2022.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />

<h3>2. Product Granular Drill-Downs & Executive Insights</h3>
<p>Page navigation allowing users to inspect itemized product details and strategic recommendations:</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="33%" align="center" valign="top">
        <h4>Granular Transaction Details</h4>
        <img src="https://i.postimg.cc/Bv2MH8rf/dytylz.png" width="95%" alt="Item Details Page" />
        <p align="left"><small>Itemized invoice and line-item table.</small></p>
      </td>
      <td width="33%" align="center" valign="top">
        <h4>Laptop Category Focus</h4>
        <img src="https://i.postimg.cc/7LSm0CFk/labtwb-dytylz.png" width="95%" alt="Laptop Category Drilldown" />
        <p align="left"><small>Product-specific drill-down for laptops.</small></p>
      </td>
      <td width="33%" align="center" valign="top">
        <h4>Performance Insights & Recommendations</h4>
        <img src="https://i.postimg.cc/jjyZPWGB/byrfwrmans-ansayts.png" width="95%" alt="Performance Insights" />
        <p align="left"><small>Actionable executive summary.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />
<hr />
<br />

<h2>💡 Strategic Recommendations & Insights</h2>
<ol>
  <li><b>High-ROI Category Prioritization:</b> Electronics (specifically Laptops) yielded the highest ROI and profit margins; marketing campaigns should focus on high-spec models.</li>
  <li><b>Inventory Turn Optimization:</b> Use detailed line-item reporting to identify slow-moving retail SKUs and apply targeted promotional discounts.</li>
  <li><b>User-Centric Reporting:</b> Page navigation buttons reduce cognitive load for decision-makers, providing quick access to both summary KPIs and row-level details.</li>
</ol>

<br />
<hr />
<br />

<h2>📂 Repository Architecture</h2>
<pre>
├── Data/                        # Raw retail sales datasets
├── Reports/                     # Retail_Sales_ROI_Analytics.pbix
├── Screenshots/                 # Interactive navigation walkthroughs
└── README.md                    # Project documentation
</pre>
