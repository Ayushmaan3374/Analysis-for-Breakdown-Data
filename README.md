# 🛠 Maintenance Breakdown Analysis (2022–2025)

## 📘 Project Overview
This project focuses on analyzing maintenance breakdown trends and related costs across multiple equipment manufacturers over the period 2022–2025. Using historical maintenance log data (`PM01.csv`), it uncovers patterns that help reduce unplanned downtime and financial loss.

## 🎯 Objective
- Identify manufacturers and equipment types contributing most to breakdowns and costs.
- Generate insights to support preventive maintenance planning, procurement strategy, and resource allocation.

## 🗃️ Data Description
File: `PM01.csv`

**Key Features:**
- `Equipment_ID`: Unique identifier for each machine.
- `Manufacturer`: Equipment source/vendor details.
- `Timestamp`: Maintenance log date and time.
- `Breakdown_Flag`: Binary indicator of breakdown occurrence.
- `Cost`: Associated maintenance cost per event.

## 🔍 Methods Used
- **Preprocessing**: Handling missing values, standardizing timestamps, and filtering noise.
- **Exploratory Data Analysis (EDA)**:
  - Monthly trend analysis
  - Breakdown frequency distributions
  - Cost aggregation across manufacturers
- **Visualization Tools**:
  - Heatmaps for cost concentration
  - Bar charts for manufacturer-wise performance
  - Time-series plots for breakdown trends

## 📈 Key Outputs
- Monthly breakdown and cost trends
- Manufacturer performance dashboards
- Visualizations pinpointing high-risk equipment types
- Actionable insights to optimize maintenance schedules

## 🔧 Tech Stack
- Python (pandas, matplotlib, seaborn, NumPy)
- Jupyter Notebook (for interactive analysis)
- Plotly (for dynamic dashboards)
