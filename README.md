# RF Universe Tools

Welcome to **RF Universe Tools**, a collection of custom-built utilities designed to assist Radio Frequency engineers in analyzing, optimizing, and troubleshooting 4G and 5G wireless networks.

These tools were developed with a focus on real-world use cases encountered in modern cellular deployments, including LTE to 5G swaps, ENDC optimization, KPI monitoring, and network visualization.

## 📦 Features

- 📈 **KPI Trend Analyzer**: Compare pre- and post-migration performance by eNodeB or sector.
- 🗺️ **Map Visualization**: Generate QGIS-compatible polygons and visualize cell status or RSSI imbalance.
- 🔍 **Worst Cell Detector**: Quickly identify top offending cells based on custom thresholds.
- ⚙️ **MRO HO Failure Analyzer**: Parse MRO data to detect worst handover failures and generate action plans.
- 📊 **Excel Report Generator**: Export analysis results into clean, standardized Excel reports.
- 🧠 **Formula Mapping Tool**: Map KPIs between vendors (Nokia, Samsung, Ericsson) for unified tracking.

## 🛠️ Built With

- Python
- Pandas
- Tkinter (GUI)
- Matplotlib / PyQtGraph
- openpyxl
- QGIS (for spatial outputs)

## 🚀 Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/rf-universe-tools.git
cd rf-universe-tools
pip install -r requirements.txt
