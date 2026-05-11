# E-Commerce Sales Analysis Dashboard

## 📊 Project Overview
This project provides a deep dive into e-commerce transaction data to track business health, profitability, and customer reach. By combining order details with geographical data, the analysis identifies key growth drivers and areas for operational improvement.

The centerpiece of this project is an interactive **Power BI Dashboard** that transforms raw CSV data into visual intelligence.

## 📁 Repository Structure
* **`Details.csv`**: Transactional data including amounts, profits, quantities, and product categories.
* **`Orders.csv`**: Logistical data containing order dates, customer names, and delivery locations (State/City).
* **`First Report.pbix`**: The compiled Power BI report file.

## 🚀 Key Insights & Metrics
The dashboard focuses on the following Key Performance Indicators (KPIs):
* **Total Sales & Profitability**: Analysis of margins across Electronics, Clothing, and Furniture.
* **Category Drill-down**: Performance tracking of sub-categories like Printers, Phones, Chairs, and Saree.
* **Geographic Distribution**: Sales heatmaps across states like Maharashtra, Madhya Pradesh, and Uttar Pradesh.
* **Payment Dynamics**: Breakdown of transactions by COD, EMI, Credit Card, and UPI.
* **Customer Trends**: Identification of high-value customers and repeat purchase patterns.

## 🛠️ Data Model
The project utilizes a relational data model linking `Details.csv` and `Orders.csv` via the **Order ID** field. This allows for seamless filtering of financial metrics by date and location.

## 📖 How to Use
1.  **Clone the Repo**:
    ```bash
    git clone https://github.com/your-username/ecommerce-analysis.git
    ```
2.  **Open the Report**: Launch `First Report.pbix` using Power BI Desktop.
3.  **Refresh Data**: If the visualizations do not appear, ensure the data source paths point to the local copies of `Details.csv` and `Orders.csv`.

## 📈 Sample Visualizations
*(You can add screenshots of your dashboard here in the future)*
- Monthly Profit Trends
- Sales by State (Map Visual)
- Category-wise Quantity Distribution
