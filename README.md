# 🔥 Australia Wildfire Dashboard

This project is an interactive web dashboard built with **Plotly Dash** to explore and visualize wildfire data across Australian regions over the years.

## 📊 Dashboard Overview

The application allows users to:

- Select a **region** (e.g., New South Wales, Queensland, etc.)
- Select a **year** (from 2005 to 2020)
- View two dynamic charts:
  - **Pie Chart**: Monthly average of estimated fire area
  - **Bar Chart**: Monthly average count of pixels indicating vegetation fires

## 📁 Dataset

The dataset contains wildfire information such as:

- **Date** of detection
- **Region** (abbreviated names of Australian states)
- **Estimated fire area**
- **Count** of pixels for presumed vegetation fires

**Note:** The original dataset was provided through IBM Skills Network, but you can use a local file named `Hotspot.csv`.

## 🛠️ Technologies Used

- Python 3.8+
- Dash by Plotly
- Plotly Express
- Pandas

## 🚀 How to Run the App

### 1. Clone the repository

```bash
git clone https://github.com/your-username/australia-wildfire-dashboard.git
cd australia-wildfire-dashboard
```

### 2. Install dependencies

```bash
pip install pandas dash plotly
```

### 3. Make sure `Hotspot.csv` is in the same directory

If the dataset is missing, either download it from the course or use a sample version manually created.

### 4. Run the application

```bash
python Dash_wildfire.py
```

The app will run on `http://127.0.0.1:8050/` by default.

## 🖼️ Screenshots

| Region Selector | Charts Output |
|-----------------|----------------|
| ![selector](screenshots/selector.png) | ![charts](screenshots/charts.png) |

## 📦 Project Structure

```
├── Dash_wildfire.py       # Main app file
├── Hotspot.csv            # Dataset file
├── README.md              # Project documentation
└── requirements.txt       # (Optional) list of dependencies
```

## 📌 Features

- Clean and intuitive UI
- Responsive visualizations
- Dynamic callbacks based on user input
- Monthly trends comparison

## 📅 Future Improvements

- Add map visualization (using Folium or Mapbox)
- Enhance filtering (multi-year range, specific months)
- Deploy online using Render or Heroku

## 🧑‍💻 Author

**Mahmoud Elzayat**  
[LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)  
Email: mahmoudelzeiat7@gmail.com  

---

## 📜 License

This project is for educational purposes. You are free to use or modify it for learning and development.
