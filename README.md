Power BI Dashboard: Heart Attack Risk Analysis
By: Mohammad Al Bayyari

📌 Overview
This Power BI Dashboard was designed to analyze heart attack risk factors using synthetic patient data. The project focused on demographics, cholesterol levels, and high-risk conditions (smoking, diabetes, high cholesterol) to identify trends and support preventative healthcare strategies.

🎯 Project Goal
The objective was to answer three critical healthcare-related questions that could help clinicians, researchers, and policymakers identify high-risk patients and tailor interventions accordingly.

🔹 Key Questions & Insights from the Dashboard
📌 Question 1: What is the demographic distribution of heart attack cases across age and gender?
💡 Business Impact: Helps tailor healthcare programs based on high-risk age groups and gender-specific risk trends.

✅ Insights from the Dashboard:
Heart attacks are most prevalent in patients aged 40-59, with the highest number of cases observed in the 40-49 and 50-59 age groups.
Men have significantly higher heart attack rates than women, indicating a gender disparity in cardiovascular health risks.
A slicer was added to dynamically filter by age ranges, allowing further demographic segmentation.
📊 Dashboard Features:
✔ Bar Chart (Age Group vs. Heart Attacks) → Displays the number of heart attack cases per age range.
✔ Bar Chart (Gender vs. Heart Attacks) → Compares cases between males and females.
✔ Age Range Slicer → Enables dynamic filtering for deeper analysis.

📌 Question 2: How do cholesterol levels impact heart attack risk, and what are the safe thresholds?
💡 Business Impact: Supports clinicians in setting cholesterol management guidelines to reduce heart attack risk.

✅ Insights from the Dashboard:
The histogram analysis shows that most heart attack patients had total cholesterol levels between 180-250 mg/dL.
Patients with cholesterol above 240 mg/dL were at the highest risk, aligning with real-world medical guidelines for high cholesterol.
Conditional formatting in the patient table highlights individuals with dangerously high cholesterol, making it easy to identify at-risk patients.
📊 Dashboard Features:
✔ Histogram (Cholesterol vs. Heart Attack Cases) → Shows the cholesterol distribution of heart attack patients.
✔ Conditional Formatting in Table → Highlights patients with high cholesterol in red.
✔ Quartile Ranges for Cholesterol → Defined in the legend to show safe vs. dangerous levels.

📌 Question 3: What percentage of high-risk patients (diabetics, smokers, high cholesterol) have not yet had a heart attack?
💡 Business Impact: Helps identify at-risk patients before a heart attack occurs, enabling preventative interventions.

✅ Insights from the Dashboard:
399 patients were identified as "high-risk" due to smoking, diabetes, or high cholesterol.
318 high-risk patients have NOT yet had a heart attack, meaning 79.7% of high-risk patients could still benefit from preventative care.
The pie chart shows the breakdown of high-risk factors, indicating that high cholesterol is the most common risk factor, followed by smoking and diabetes.
📊 Dashboard Features:
✔ KPI Cards → Display total high-risk patients, high-risk patients without a heart attack, and the percentage of high-risk patients without a heart attack.
✔ Pie Chart (Risk Factor Breakdown) → Shows the proportion of smokers, diabetics, and high cholesterol patients.
✔ Filtered Table (At-Risk Patients Without a Heart Attack) → Displays patient details with risk factors.

🔹 Additional Features Implemented
✔ Custom Data Transformation: Created a unique Patient_ID using Power Query to ensure each patient was identifiable.
✔ Dynamic Filtering: Added slicers for age range to allow detailed segmentation of heart attack cases.
✔ Data Visualization Enhancements: Applied color coding & conditional formatting to make risk levels visually clear.
✔ KPI Indicators for Quick Insights: Designed KPI cards to show key risk statistics at a glance.
