# Remote Work, Burnout, and Social Isolation

**Tableau Analysis Project**

---

## Ask

In this project, I take on the role of a **data analyst at a company** tasked with identifying trends in employee wellbeing. The goal is to analyze survey data to uncover patterns in **burnout** and **social isolation** across different work arrangements, helping leadership understand potential areas of concern and opportunities to improve employee experience.

This project explores how work arrangement (remote, hybrid, on-site) relates to employee burnout and social isolation.

Intuitively, remote work is often assumed to reduce burnout because it removes commuting, increases flexibility, and allows for greater autonomy. At the same time, remote work is expected to increase social isolation due to reduced in-person interaction.

The central question of this analysis is:

- How do burnout levels and social isolation differ across remote, hybrid, and on-site workers?  
- Does the relationship change when isolating specific industries and job role types?  

---

## Prepare

The dataset consists of employee survey responses with the following relevant fields:

- Work_Arrangement  
- Burnout_Level  
- Social_Isolation_Score  
- Industry  
- Job_Role  
- Gender  
- Region  

The data was imported into Tableau Public and reviewed for completeness and consistency. Burnout was captured as a categorical variable (Low / Medium / High), while social isolation was measured using a numeric score.

---

## Process

Two key methodological decisions shaped this project:

### 1. Measuring burnout using percentages, not averages
An early challenge was determining how to visualize burnout correctly. Because burnout is categorical, averaging it into a single score produced misleading results. Instead, burnout was analyzed as the percentage distribution of Low, Medium, and High responses within each group. This better reflects how burnout is actually experienced across workers.

### 2. Limiting filters to avoid over-fragmentation
To keep the analysis focused and interpretable, only two filters were used:

- **Industry** (kept as provided in the dataset)  
- **Job Role (Grouped)**

Individual job roles were grouped into four broader categories to reduce noise and improve analytical clarity:

- Technical / Specialist  
- Customer-Facing / Support  
- Management / Leadership  
- Marketing / Content  

This allowed for meaningful comparisons without creating overly granular slices of data that would be difficult to interpret.

---

## Analyze

### Overall pattern (no filters applied)

Before isolating any industries or job roles, a clear and consistent pattern emerged across the full dataset:

**Burnout**  
- Remote workers report the highest levels of burnout  
- Hybrid workers fall in the middle  
- On-site workers report the lowest burnout  

This result is surprising given the common assumption that remote work should reduce burnout by eliminating commutes and increasing flexibility.

**Social Isolation**  
- Remote workers report the highest social isolation scores  
- Hybrid workers report moderate isolation  
- On-site workers report the lowest isolation  

Unlike burnout, the social isolation result aligns closely with intuitive expectations.

### Targeted experiments

**Experiment 1: Roles and industries well-suited for remote work**  
Industries and job role groups typically considered remote-friendly were isolated (e.g., technology-focused industries and technical/specialist roles).

Even in this context:

- Remote workers still showed a higher proportion of high burnout compared to hybrid and on-site workers  
- Social isolation remained highest among remote workers

**Experiment 2: Roles and industries better suited for on-site work**  
Customer-facing roles in industries such as healthcare and retail were isolated to represent work that benefits from in-person interaction.

In this scenario:

- On-site workers showed the highest proportion of low burnout  
- Remote workers again reported the highest burnout and social isolation

---

### Key insight

Across both experiments and the overall dataset, the pattern remained consistent:

- Remote work is associated with higher burnout, not lower  
- Hybrid work tends to moderate both burnout and isolation  
- On-site work shows the lowest burnout and social isolation  

This suggests that flexibility alone does not necessarily protect against burnout, and that reduced social connection may play a larger role than expected.

---

## Share / Act

These findings challenge common assumptions about remote work and highlight important trade-offs:

- Organizations should not assume remote work automatically reduces burnout  
- Hybrid arrangements may offer a balance between flexibility and social connection  
- Remote roles may require intentional interventions to address isolation and workload boundaries

Future analysis could explore:

- The role of hours worked in mediating burnout  
- Differences by career stage or tenure  
- Longitudinal trends over time

---

## Tools Used

- Tableau Public  
- Survey dataset (self-reported employee responses)  

[Link to interactive Tableau dashboard]
