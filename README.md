# Post-Pandemic Work Health (Tableau Project)

This project explores the relationship between work arrangements (**remote**, **hybrid**, **onsite**) and employee well-being using survey data.

---

## 🧠 Key Questions

1. How do mental health outcomes differ across work arrangements?  
2. What is the relationship between work-life balance, burnout, and hours worked?  
3. How do demographic and salary differences shape health impacts?

---

## 🧹 Data Cleaning & Preparation

The dataset was mostly clean, but I conducted a thorough inspection to confirm data quality and consistency before analysis. I checked for missing values using filters and conditional formulas, verified categorical consistency to ensure “Remote,” “Hybrid,” and “Onsite” were entered uniformly, tested for extra spaces or hidden characters using the `TRIM()` and `CLEAN()` functions, confirmed data types for numerical and date fields to support accurate analysis in Tableau, and reviewed duplicates to ensure each record represented a unique response. Overall, the dataset required minimal cleaning, with only light formatting adjustments before visualization.

---

## 🧰 Tools Used

- **Google Sheets** — for data inspection and light cleaning  
- **Tableau** — for data visualization and analysis  

---

## First Analysis: Mental Health Outcomes by Work Arrangement

To begin exploring mental health outcomes, I ran a basic visualization in Tableau Public to examine the **average Social Isolation Score** for each work arrangement across the full dataset, without focusing on any specific industry. This approach provides a broad overview of trends and serves as a starting point for deeper analysis. The visualization shows that, overall, remote workers report the **highest average social isolation scores**, followed by hybrid workers, with onsite workers showing the lowest scores. This result aligns with intuitive expectations: on average, remote work can lead to higher feelings of social isolation. While many additional variables could affect mental health outcomes, this simple overview demonstrates a clear trend and highlights the value of interactive data visualization in understanding workforce well-being.

**Interactive Viz:**  
Explore the chart on Tableau Public: [View here](https://public.tableau.com/views/MentalHealthOutcomesbyWorkArrangements/Sheet1)
