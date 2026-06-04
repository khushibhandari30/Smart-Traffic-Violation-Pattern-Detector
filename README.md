# 🚦 Smart Traffic Violation Pattern Detector Dashboard 
 A Streamlit-based dashboard to analyze, visualize, and detect patterns in traffic violation data using interactive charts, maps, and trend analysis.


##  Overview

This project is a Streamlit web application designed to analyze traffic violation data. It provides a user-friendly interface to explore, visualize, and gain insights from traffic violation datasets.

>  **Documentation**: For a comprehensive understanding of the project, please refer to our detailed core documentation:
>
> * **[1. System Architecture (Basic)](PROJECT_DOCUMENTATIONS/PROJECT_BLUEPRINT_1-BASIC.md)**: High-level overview, architecture diagrams, and directory structure.
> * **[2. Page Development Details](PROJECT_DOCUMENTATIONS/PROJECT_BLUEPRINT_2-PAGE_DEVELOPMENT_DETAILS.md)**: In-depth analysis of each page, purpose, and dependencies.
> * **[3. Visual Diagrams](PROJECT_DOCUMENTATIONS/PROJECT_BLUEPRINT_3-VISUAL_DIAGRAMS.md)**: Detailed Architecture, Data Flow, and Component Interaction diagrams.

##  Features

* **Dataset Management:**
  * Upload your own CSV datasets.
  * View and browse the loaded dataset.
* **Numerical Analysis:**
  * Get a quick overview of your dataset, including shape and sample rows.
  * View detailed information about each column, including data types and descriptive statistics.
* **Data Visualization:**
  * Generate various plots to visualize data distributions and relationships.
* **Trend Analysis:**
  * Analyze trends in the data over time.
* **Map Visualization:**
  * Visualize geographical data on an interactive map.
* **Correlation Analysis:**
  * Explore correlations between numerical columns with a heatmap.

##  Use Cases

- Traffic police departments analyzing violation trends
- Smart city planners identifying high-risk zones
- Data analysts exploring real-world public datasets
- Academic projects and demonstrations of data visualization




##  How to Run

1. **Clone the repository:**

    ```bash
    git clone https://github.com/khushibhandari30/Smart-Traffic-Violation-Pattern-Detector.git
    cd Smart-Traffic-Violation-Pattern-Detector
    ```

2. **Choose your package manager:**

    ---

   ### Primary Method:  Using `pip`

    1. **Create and activate a virtual environment:**

        ```bash
        python -m venv .venv
        
        # Activate the virtual environment
        # On Windows (Command Prompt)
        .\.venv\Scripts\activate
        # On Windows (PowerShell)
        .\.venv\Scripts\Activate.ps1
        # On macOS/Linux
        source .venv/bin/activate
        ```

    2. **Install dependencies:**

        ```bash
        pip install .
        ```

    3. **Run the application:**

        ```bash
        streamlit run main.py
        ```

##  Project Structure

```text
.
├── .idea
├── artifact file
│   ├── Agile_Template_v0.1.xlsx
│   ├── Defect_Tracker Template_v0.1.xlsx
│   ├── Unit_Test_Plan_v0.1.xlsx
├── images
│   ├── smart_traffic.jpg
├── styles
│   ├── main.css
├── views
│   ├── _1_Home.py
│   ├── _2_Dashboard.py
│   ├── _3_Time_Trend_Analysis.py
│   ├── _4_Environment_Analysis.py
│   ├── _5_Vehicle_Analysis.py
│   ├── _6_Driver_Behaviour_Analysis.py
│   ├── _7_Payment_Analysis.py
│   ├── _8_Map_Visualisation.py
│   ├── _9_Report.py
│   └── _10_About.py
├── generate_cleaned_data.py
├── india_states.geojson
├── Indian_Traffic_Violations.csv
├── main.py
├── README.md
├── requirements.txt
├── utils.py
├── world.geojson

```

##  Dependencies

The main dependencies for this project are listed in the `pyproject.toml` file. They include:

* `streamlit>=1.28` - [Streamlit](https://streamlit.io/)
* `pandas>=2.0` - [Pandas](https://pandas.pydata.org/)
* `numpy>=1.23` - [Numpy](https://numpy.org/)
* `matplotlib>=3.7` - [Matplotlib](https://matplotlib.org/)
* `seaborn>=0.12` - [Seaborn](https://seaborn.pydata.org/)
* `plotly>=5.15` - [Plotly](https://plotly.com/)
* `folium>=0.14` - [Folium](https://python-visualization.github.io/folium/)
* `streamlit-folium>=0.15` - [Streamlit Folium](https://pypi.org/project/streamlit-folium/)
* `requests>=2.31` - [Requests](https://pypi.org/project/requests/)

##  Future Enhancements

- Machine Learning–based violation prediction
- Real-time data ingestion via APIs
- User authentication and role-based access
- Automated report generation (PDF)



---
