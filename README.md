# 🔍 Global Homicide Data Analysis

A data analysis and visualisation project exploring global homicide trends using Python, Pandas, and Plotly. The project covers country-level homicide statistics worldwide, with a focused section on major South African cities.

---

 Project Structure

```
Homicide/
├── data/
│   └── homicide_by_countries.csv   # Source dataset (195 countries)
├── homicide_project.ipynb          # Main analysis notebook
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
```

---

Dataset

Source: `homicide_by_countries.csv`

| Column      | Description                              |
|-------------|------------------------------------------|
| `Location`  | Country name                             |
| `Region`    | World region (Africa, Asia, Europe, etc.)|
| `Subregion` | Sub-region classification                |
| `Rate`      | Homicide rate per 100,000 population     |
| `Count`     | Total number of homicides                |
| `Year`      | Year of the recorded data                |

- 195 rows — one per country
- No missing values
- Data spans multiple years depending on country availability

---

 Analysis Performed

### Global View
- Top 5 countries by homicide count — Brazil, Nigeria, India, Mexico, USA
- Pie chart — percentage share of total homicides among top 5 countries
- Treemap — hierarchical view of homicide counts by region/country
- Bar charts & distribution plots — rate and count comparisons across regions

### 🇿🇦 South African Cities
A dedicated section visualises homicide data for major South African cities, sourced from SAPS (South African Police Service) crime statistics:

| City                        | Province        |
|-----------------------------|-----------------|
| Johannesburg                | Gauteng         |
| Cape Town                   | Western Cape    |
| Durban (eThekwini)          | KwaZulu-Natal   |
| Pretoria (Tshwane)          | Gauteng         |
| Port Elizabeth (Gqeberha)   | Eastern Cape    |
| East London (Buffalo City)  | Eastern Cape    |
| Bloemfontein                | Free State      |
| Nelspruit (Mbombela)        | Mpumalanga      |
| Polokwane                   | Limpopo         |
| Kimberley                   | Northern Cape   |

Presented as an interactive horizontal bar chart, colour-coded by province.

---

## 🛠️ Tech Stack

| Tool            | Purpose                        |
|-----------------|--------------------------------|
| Python 3.9      | Core language                  |
| Pandas          | Data loading & manipulation    |
| Plotly Express  | Interactive visualisations     |
| Matplotlib      | Static charts                  |
| Seaborn         | Statistical visualisations     |
| Jupyter         | Notebook environment           |

---

##  Getting Started

### 1. Clone or download the project

```bash
git clone <your-repo-url>
cd "Project 4"
```

### 2. Create and activate a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter and open the notebook

```bash
jupyter notebook homicide_project.ipynb
```

---

## 📌 Key Insights

- Brazil records the highest total homicide count globally (~47,700)
- Venezuela has one of the highest rates (36 per 100,000 population)
- Johannesburg and Cape Town lead South African cities in total homicide counts
- Southern Africa and Latin America consistently show the highest homicide rates worldwide

---

## 📄 License

This project is for educational and portfolio purposes.
