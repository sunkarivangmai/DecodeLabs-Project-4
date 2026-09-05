DecodeLabs Project 4 — Data Visualization

Objective

Transform the Project 2 e-commerce dataset from raw analysis into decision-ready visual communication.

This project follows the supplied Project 4 blueprint:

Architect — Choose with Purpose

Start with the business question.

Match the chart type to the analytical need.

Keep axes honest; no 3D or distortion.

Editor — Edit with Precision

Reduce chartjunk.

Prefer direct labels.

Use visual emphasis only for the core insight.

Storyteller — Tell a Story

Use action-oriented titles.

Keep one main message per slide.

Explain the “So What?” using Situation → Complication → Resolution.

Files

Project_4_Data_Visualization.xlsx — executive dashboard, chart data, visualization notes, and source data.

Project4_Data_Visualization.pptx — boardroom-style presentation with one core message per slide.

project4_visualization.ipynb — reproducible Python visualization workflow.

requirements.txt — Python dependencies.

charts/ — exported visualization images used in the presentation.

Key findings

Total revenue: ₹1,264,761.96

Orders: 1,200

Unique customers: 1,189

Average order value: ₹1,053.97

Median order value: ₹823.62

Top revenue product: Chair (₹195,620.11)

Second revenue product: Printer (₹195,612.61)

Delivered orders: 231 (19.2%)

Cancelled + returned: 497 (41.4%)

Important data caveat

The dataset contains 2025 records only through June. Therefore, 2025 should not be treated as a complete-year comparison against 2023 or 2024.

How to run the notebook

pip install -r requirements.txt
jupyter notebook project4_visualization.ipynb

Suggested GitHub structure

DecodeLabs-Project-4-Data-Visualization/
├── README.md
├── requirements.txt
├── Project4_Data_Visualization.pptx
├── Project_4_Data_Visualization.xlsx
├── project4_visualization.ipynb
└── charts/
    ├── revenue_by_product.png
    ├── monthly_revenue_trend.png
    ├── order_status.png
    └── quantity_vs_order_value.png
