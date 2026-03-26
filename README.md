# childcare-affordability-analysis
Analyzed U.S. childcare affordability using county-level data to identify cost burdens, geographic disparities, and policy-relevant insights through data visualization and storytelling.

# Childcare Affordability Analysis (U.S. Counties)

##  Overview
This project analyzes childcare affordability across U.S. counties using data from the National Database of Childcare Prices. The goal is to identify cost burdens, geographic disparities, and policy-relevant insights through data visualization and storytelling.

---

##  Problem Statement
Childcare is one of the largest household expenses in the United States and significantly impacts workforce participation and financial stability. Policymakers and organizations need data-driven insights to understand where affordability challenges are most severe.

---

##  Dataset
- National Database of Childcare Prices (U.S. Department of Labor)
- County-level data
- Year: 2018
- Variables:
  - Weekly childcare costs (infants, toddlers, preschool)
  - Center-based vs family childcare
  - Median household income

---

##  Methods

### Data Preparation
- Filtered dataset to 2018
- Removed missing and invalid values
- Standardized columns and data types :contentReference[oaicite:0]{index=0}  

### Feature Engineering
- Annual childcare cost = weekly cost × 52  
- Affordability ratio = childcare cost / income :contentReference[oaicite:1]{index=1}  

---

##  Analysis & Visualizations

- Childcare cost comparison by age group
- Affordability burden distribution
- Top states by affordability burden
- Income vs childcare cost relationship
- Cost gap between provider types
- Dashboard mockup and infographic

---

##  Key Insights

- Infant childcare is the most expensive category across all age groups :contentReference[oaicite:2]{index=2}  
- Center-based childcare is consistently more expensive than family childcare :contentReference[oaicite:3]{index=3}  
- Affordability varies significantly across counties and states  
- Higher income does not always eliminate affordability challenges  
- Geographic disparities indicate the need for targeted policy solutions  

---

##  Business / Policy Value

- Supports data-driven policy decisions  
- Identifies high-burden regions  
- Helps guide resource allocation and subsidy programs  
- Improves understanding of childcare cost inequality  

---

##  Communication Approach

This project uses multiple formats to communicate insights:

- Policy presentation → decision-makers  
- Dashboard concept → analysts  
- Infographic → general public  

---

##  Ethical Considerations

- No personally identifiable data used  
- Results represent correlations, not causation  
- Data filtering may introduce bias  
- Interpretation avoids overgeneralization :contentReference[oaicite:4]{index=4}  

---

##  Project Structure

- `.ipynb` → analysis & visualizations  
- `.pdf / .docx` → full report  
- `.pptx` → presentation  

---

##  Author
Shaghayegh Malekshahi  
Master’s in Data Science – Bellevue University
