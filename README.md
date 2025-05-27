# 📊 CSV Data Visualization Web App

An interactive web application to upload, filter, analyze, and visualize CSV data — designed to function like a lightweight Power BI alternative. Built using HTML, JavaScript (Plotly, PapaParse, Luxon), and TailwindCSS.
[WEBSITE LIMK ] https://mydatavisual.netlify.app/
## 🚀 Features

- 📁 **CSV Upload**: Upload and parse any CSV file with header rows.
- 🧠 **Automatic Data Type Detection**: Identifies numeric, categorical, and date fields.
- 🎛️ **Dynamic Filters**:
  - Multi-select filters for categorical fields
  - Date range picker for date fields
- 📈 **Visualizations**:
  - **Bar Chart**: Category count
  - **Line Chart**: Numeric trend over time
  - **Pie Chart**: Category distribution
- 📊 **Summary Statistics**:
  - Total rows
  - Min, Max, Average for numeric fields
  - Unique value count for categorical fields
- 📱 **Responsive Design** using TailwindCSS
- 📉 **Auto-refresh charts and stats** on filter change

## 🖼️ Demo

![Demo GIF](https://github.com/sathyasrikarthikeyan/Data_Visualization_app/blob/main/demo.gif)

## 📂 Project Structure

├── index.html # Main dashboard (HTML, JS, Tailwind, Plotly)
├── /assets # Icons, fonts, or future extensions
└── README.md

markdown
Copy
Edit

## 📦 Technologies Used

- [Plotly.js](https://plotly.com/javascript/) – Interactive charts
- [PapaParse](https://www.papaparse.com/) – CSV parser
- [Luxon](https://moment.github.io/luxon/) – Date parsing and manipulation
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling
- Vanilla JavaScript – Logic for data processing and filtering

## 🛠️ Setup & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/sathyasrikarthikeyan/Data_Visualization_app.git
   cd Data_Visualization_app
Open index.html in your browser:

You can simply open it by double-clicking or dragging into a browser window.

Upload your CSV file and explore:

Filters will automatically appear based on your CSV structure.

✅ No server setup or backend required — runs fully in the browser.

📌 Example Use Cases
Business data visualization

Quick insights into datasets

Analytics for non-technical users

🧠 Author
Sathya Sri Karthikeyan
GitHub Profile
Feel free to ⭐️ the repo or contribute!
