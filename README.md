<body>

<h1>🌟 AdventureWorks Data Analysis Dashboard</h1>
<img src="https://upload.wikimedia.org/wikipedia/commons/6/63/AdventureWorks.png" alt="AdventureWorks Logo" width="150">

<h2>📊 Visualizing Business Insights with Interactive Dashboards</h2>
<p>Welcome to the <strong>AdventureWorks Data Analysis Dashboard</strong> repository! This project showcases an in-depth analysis of AdventureWorks' business performance, visualized through stunning and interactive Power BI dashboards.</p>

<hr>

<h2>🔍 Key Highlights</h2>
<ul>
    <li><strong>Fiscal Year Analysis</strong>: Gain insights into total revenue, profit, and order volumes.</li>
    <li><strong>Category Breakdown</strong>: Explore sales, profit, and margins across categories like Bikes, Accessories, and Components.</li>
    <li><strong>Calendar Heatmap</strong>: Visualize sales trends over time with a heatmap for quick pattern detection.</li>
    <li><strong>Profitability Analysis</strong>: Compare average costs, sales prices, and profit margins across products.</li>
    <li><strong>Geographic Insights</strong>: Map sales across different cities in Australia and globally.</li>
    <li><strong>Customer and Reseller Drillthroughs</strong>: Dive deep into individual customer and reseller performance.</li>
</ul>

<hr>

<h2>🧑‍💻 DAX Sample Model</h2>
<p>The <strong>Adventure Works DW 2020</strong> Power BI Desktop sample model is designed to support your DAX learning. The model is based on the <a href="https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=tsql#data-warehouse-downloads">Adventure Works data warehouse sample</a> for AdventureWorksDW2017—but the data has been modified and updated to 2020 to suit the objectives of the sample model.</p>

<h3>🌐 Scenario</h3>
<img src="https://docs.microsoft.com/en-us/power-bi/guidance/media/dax-sample-model/adventure-works-logo-150x150.png" alt="AdventureWorks Logo" width="150">
<p>The Adventure Works company represents a bicycle manufacturer that sells bicycles and accessories to global markets. The company stores its data warehouse data in an Azure SQL Database.</p>

<h3>📁 Model Structure</h3>
<table>
    <thead>
        <tr>
            <th>Table</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Customer</strong></td>
            <td>Describes customers and their geographic location. Customers purchase products online (Internet sales).</td>
        </tr>
        <tr>
            <td><strong>Date</strong></td>
            <td>Captures order, ship, and due dates. The fiscal year starts on July 1. The table is marked as a date table using the <strong>Date</strong> column.</td>
        </tr>
        <tr>
            <td><strong>Product</strong></td>
            <td>Contains finished products only.</td>
        </tr>
        <tr>
            <td><strong>Reseller</strong></td>
            <td>Describes resellers and their geographic location. Resellers sell products to their customers.</td>
        </tr>
        <tr>
            <td><strong>Sales</strong></td>
            <td>Stores sales data at the order line grain. All financial values are in USD, with order dates ranging from July 1, 2017, to June 15, 2020.</td>
        </tr>
        <tr>
            <td><strong>Sales Order</strong></td>
            <td>Contains details about sales orders and sales channels (Reseller or Internet). This table has a one-to-one relationship with the <strong>Sales</strong> table.</td>
        </tr>
        <tr>
            <td><strong>Sales Territory</strong></td>
            <td>Organizes territories into groups (North America, Europe, and Pacific), countries, and regions. Only the United States has regional data.</td>
        </tr>
    </tbody>
</table>

<hr>

<h2>📸 Screenshots</h2>
<h3>💰 Company Performance Overview</h3>
<img src="./screenshots/Screenshot_1.png" alt="Company Performance" width="600">

<h3>📅 Calendar Heatmap View</h3>
<img src="./screenshots/Screenshot_2.png" alt="Calendar Heatmap" width="600">

<h3>🎉 Highlight Period / Holiday Season</h3>
<img src="./screenshots/Screenshot_3.png" alt="Holiday Sales" width="600">

<h3>💡 Profit Margin Analysis</h3>
<img src="./screenshots/Screenshot_4.png" alt="Profit Margin" width="600">

<h3>🌍 Map View</h3>
<img src="./screenshots/Screenshot_5.png" alt="Map Insights" width="600">

<h3>👥 Customer Inquiry</h3>
<img src="./screenshots/Screenshot_6.png" alt="Customer Details" width="600">

<h3>🛍️ Reseller Inquiry</h3>
<img src="./screenshots/Screenshot_7.png" alt="Reseller Details" width="600">

<hr>
<hr>

<h2>🚀 Getting Started</h2>
<ol>
    <li><strong>Clone this repository:</strong>
        <pre>git clone https://github.com/Kevinbui16/AdventureWorks-Data-Analysis-Dashboard.git</pre>
    </li>
    <li><strong>Explore the Dashboards:</strong>
        Open the <code>AdventureWorks.pbix</code> file using Power BI Desktop.
    </li>
    <li><strong>DAX Learning:</strong>
        Load the <strong>Adventure Works DW 2020</strong> sample model for hands-on DAX practice.
    </li>
</ol>

<hr>

<h2>🤝 Contributions</h2>
<p>Contributions are welcome! Feel free to create a pull request or open an issue for suggestions.</p>

<hr>

<h2>📧 Contact</h2>
<p>For any queries, reach out to <strong>khoinguyenbui2004@gmail.com</strong>.</p>

</body>
</html>
