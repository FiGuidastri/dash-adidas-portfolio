# Adidas Interactive Sales Dashboard 📊

An interactive sales analytics dashboard built with Streamlit for visualizing Adidas sales data across different retailers, regions, and time periods.

![Adidas Logo](adidas-logo.jpg)

## 🎯 Features

- **Real-time Sales Metrics**: View up-to-date sales performance data
- **Retailer Analysis**: Compare total sales across different retailers
- **Time-series Analysis**: Track sales trends over months and years
- **Geographic Insights**: Analyze sales performance by state, region, and city
- **Interactive Visualizations**:
  - Bar charts for retailer-wise sales comparison
  - Line charts for sales trends over time
  - Dual-axis charts showing total sales and units sold by state
  - Treemap visualization for regional and city-level sales
- **Data Export**: Download filtered data in CSV format for further analysis
- **Expandable Data Views**: Explore detailed data within the dashboard

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/FiGuidastri/dash-adidas-portfolio.git
cd dash-adidas-portfolio
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

### Usage

Run the Streamlit application:
```bash
streamlit run app.py
```

The dashboard will open in your default web browser at `http://localhost:8501`.

## 📦 Technologies Used

- **[Streamlit](https://streamlit.io/)**: Web application framework
- **[Pandas](https://pandas.pydata.org/)**: Data manipulation and analysis
- **[Plotly](https://plotly.com/)**: Interactive visualization library
- **[Pillow](https://python-pillow.org/)**: Image processing
- **[openpyxl](https://openpyxl.readthedocs.io/)**: Excel file handling

## 📁 Project Structure

```
dash-adidas-portfolio/
│
├── app.py                 # Main Streamlit application
├── Adidas.xlsx           # Sales data source
├── adidas-logo.jpg       # Brand logo
├── requirements.txt      # Python dependencies
└── README.md            # Project documentation
```

## 📊 Data Structure

The dashboard uses an Excel file (`Adidas.xlsx`) containing Adidas sales data with the following key fields:

- **Retailer**: Store or retailer name
- **InvoiceDate**: Date of sale
- **State**: U.S. state where sale occurred
- **Region**: Geographic region
- **City**: City where sale occurred
- **TotalSales**: Total sales amount in dollars
- **UnitsSold**: Number of units sold

## 🎨 Dashboard Sections

1. **Header**: Displays Adidas logo and dashboard title with last update timestamp
2. **Retailer Sales**: Bar chart showing total sales by retailer
3. **Sales Over Time**: Line chart tracking monthly sales trends
4. **State Performance**: Combined bar and line chart showing sales and units sold by state
5. **Regional Treemap**: Hierarchical visualization of sales by region and city
6. **Raw Data**: Expandable sections to view and download raw data

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📝 License

This project is available for educational and portfolio purposes.

## 👤 Author

**FiGuidastri**

---

*Built with ❤️ using Streamlit and Plotly*
