# 🇺🇸 1992 U.S. Presidential Election – Interactive Data Dashboard

This R Shiny + Flexdashboard project visualizes and analyzes demographic and political data from the 1992 U.S. Presidential Election at the county level. It provides an interactive interface for exploring trends in voter turnout, population distributions, and party affiliations across different states.

---

## 🔍 Project Highlights

- **Data Source:** Three Excel datasets containing county-level information on population, age, race, income, party affiliation, and turnout.
- **Tools Used:**  
  - `flexdashboard`, `shiny`, `plotly`, `ggplot2`, `DT`, `corrplot`, `janitor`, `readxl`, and others from the tidyverse.
- **Key Features:**
  - Interactive **tables** and **summary statistics**
  - **Box-and-whisker plots** for population, party data, and turnout
  - **Density plots** for demographic variables
  - **Correlation heatmap** to identify relationships among variables
  - **Bar plots** comparing average black and white populations by state

---

## 📊 Dashboard Sections

### 1. **Table View**
- Displays average and standard deviation for key metrics (population, turnout, party support) per state.
- Downloadable as CSV, Excel, PDF, or printable.

### 2. **Box & Whisker Plots**
- Visual comparisons of state-level distributions for:
  - Population size and density
  - Democrat and Republican counts
  - Racial composition (White/Black)
  - Voter turnout

### 3. **Density Plots**
- Normality and skewness insights for variables like income, crime, college education, and racial composition.

### 4. **Correlation Matrix**
- Heatmap of Pearson correlations among numerical variables.
- Highlights strongest negative/positive relationships (e.g., between white and black population densities).

### 5. **Bar Plot**
- Side-by-side comparison of average black and white population across states.

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/1992-election-dashboard.git
   cd 1992-election-dashboard

