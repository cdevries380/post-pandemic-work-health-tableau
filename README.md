# Post-Pandemic Work Health (Tableau Project)

This project explores how work arrangement (**Remote, Hybrid, On-site**) impacts people's health outcomes. Having data on specific industries, specific conditions, countries etc allows me to look at how different groups experience post-pandemic work differently — whether certain sectors face higher burnout, or if some regions report better work-life balance than others. Overall, it’s a chance to explore how the shift in work culture has shaped people’s health and daily lives. Hope you enjoy this analysis.

---

## 🧠 Key Questions

1. How do mental health outcomes differ across work arrangements?  
2. What is the relationship between work-life balance, burnout, and hours worked?  
3. How do demographic and salary differences shape health impacts?

---

## 🧹 Data Cleaning & Preparation

The dataset was mostly clean, but I conducted a thorough inspection to confirm data quality and consistency before analysis. I checked for missing values using filters and conditional formulas, verified categorical consistency to ensure **“Remote,” “Hybrid,” and “Onsite”** were entered uniformly, tested for extra spaces or hidden characters using the `TRIM()` and `CLEAN()` functions, confirmed data types for numerical and date fields to support accurate analysis in Tableau, and reviewed duplicates to ensure each record represented a unique response. Overall, the dataset required minimal cleaning, with only light formatting adjustments before visualization.

---

## 🧰 Tools Used

- **Google Sheets** — for data inspection and light cleaning  
- **Tableau** — for data visualization and analysis  

---

## 📊 First Analysis: Social Isolation Score by Work Arrangement

To begin exploring mental health outcomes, I ran a basic visualization in Tableau Public to examine the **average Social Isolation Score** for each work arrangement across the full dataset, without focusing on any specific industry. This approach provides a broad overview of trends and serves as a starting point for deeper analysis. The visualization shows that, overall, **remote workers report the highest average social isolation scores**, followed by hybrid workers, with onsite workers showing the lowest scores. This result aligns with intuitive expectations: on average, remote work can lead to higher feelings of social isolation. 

**Interactive Viz:**  
[INSERT TABLEAU PUBLIC LINK HERE]

---

## 🔥 Second Analysis: Burnout Levels by Work Arrangement

After establishing a baseline understanding of social isolation, I wanted to look deeper into how **burnout** compares across the same work arrangements. I thought it would be important to look at a few key factors — namely **social isolation score** and **burnout level** — and how they each relate to work arrangement. I could’ve done this analysis in either Google Sheets or Tableau, but I chose **Tableau** because I like the presentation and the flexibility to create calculated fields directly in the platform using code, instead of generating new columns manually and re-uploading data.

For this analysis, I created a **calculated field** to convert burnout levels (**Low, Medium, High**) into a numerical scale, allowing me to compute average burnout scores across work arrangements. With this, I built a **bar chart comparing average burnout levels** between **Remote**, **Hybrid**, and **On-site** workers.

Interestingly, while remote workers showed the highest levels of social isolation in the first visualization, **on-site workers actually displayed the highest average burnout levels** in this one. This opens up a more nuanced conversation — perhaps on-site roles come with more rigid structures, commute stress, or managerial oversight that contribute to burnout differently than isolation does for remote workers.

*(Insert further analysis here that tells a more in-depth story on the data — for example, how other variables like job satisfaction or hours worked might interact with these findings.)*

---

## 🧩 Technical Notes

- Used **Tableau Public** for visualization and field calculations  
- Created a **calculated field** to transform categorical burnout levels into numeric scores for averaging  
- Maintained consistent **color schemes** across visualizations for clear comparison  
- Followed **best practices** for labeling, axis clarity, and layout to ensure visual storytelling quality suitable for portfolio presentation  

---

## 🔮 Next Steps / Future Analysis *(optional placeholder)*

- Explore relationships between **hours worked** and both **burnout** and **social isolation**  
- Examine **industry-specific trends** to identify sectors with higher risk factors  
- Create a **dashboard** combining multiple visualizations for a portfolio-ready interactive view  
