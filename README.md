# 📊 RMB Breakdown Viewer (Shiny Demo App)

This is a demo project showcasing a simple Shiny web application built in R. The app allows users to:

- Upload an Excel file with a predefined structure
- Visualize RMB totals using an interactive pie chart and time-series bar chart
- Toggle breakdowns by `COUNTRY`, `REGION`, or `BG` categories

> **Note:** This app is designed for demonstration and presentation purposes only. It does **not** store or process data on the server. The server simply renders plots based on locally uploaded files. This is safe for sensitive workflows, provided sensitive files remain local and are not rehosted or embedded.

---

## 🔗 Live App

👉 [Try the app on ShinyApps.io](https://h-hedman.shinyapps.io/demo_shiny/)

---

## 📁 How to Use

1. Download or clone this repo
2. Launch the app locally by opening `app.R` in RStudio
3. Upload an Excel file matching the `dummy_data.xlsx` structure:
   - Columns: `RMB`, `COUNTRY`, `REGION`, `BG`, `YEAR`, `MONTH`, etc.

---

## 🧪 Technologies Used

- R / Shiny
- `plotly` for interactive charts
- `readxl` for file upload parsing
- `ggplot2` and `RColorBrewer` for styling

---
