# Improving Ship Design Based on Titanic Survival Data

## Project Overview
This project aimed to explore the Titanic maritime tragedy with the goal of improving modern ship designs. The focus was on ensuring equal access to emergency exits and equipment for all passengers, regardless of class and age.

-[Tableau Dashboard](https://public.tableau.com/views/Book1_17361999221650/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Dashboard 1](https://github.com/user-attachments/assets/8156f676-6927-49ad-9616-58a4ea89494f)

## Project Structure
- **Data Collection and Preparation:**
  - Used the titanic kaggle dataset, loaded into a pandas DataFrame, and stored in a SQLite database using ipython-sql.

- **Data Analysis and Visualization:**
  - Used Pandas library to categorize passengers into age groups and export the processed DataFrame to an Excel file for use in Tableau visualizations.
  - Created visualizations in Tableau, including survival assessment, age histogram, survival percentage pie chart, survival count and percentage by class, and survival percentage by class and age category.

- **Analysis Approach:**
  - Categorized ages into Children, YouthAdults, and Seniors, examined survival rates by class and age, and utilized bar plots and pie charts to visualize insights and identify critical factors influencing survival outcomes.

## Impact and Assessment
The analysis revealed significant differences in survival rates among various passenger classes and age groups. By examining survival percentages, critical areas for improvement in ship design and emergency preparedness were identified.

## Key Findings and Recommendations
- **Disparity in Survival Rates:**
  - **Finding:** First-class passengers had a significantly higher survival rate compared to third-class passengers.
  - **Recommendation:** Reduce the survival rate gap between passenger classes by ensuring equitable safety measures and resources.

- **Age-Based Vulnerability:**
  - **Finding:** Children in second class had the highest survival rates, while seniors had the lowest survival rates across all classes.
  - **Recommendation:** Implement age-specific safety protocols and enhance accessibility for vulnerable age groups, particularly seniors.

- **Emergency Accessibility:**
  - **Finding:** Proximity to lifeboats, clear emergency instructions, and efficient evacuation procedures are critical factors influencing survival rates.
  - **Recommendation:** Prioritize these elements in ship design to improve overall passenger safety.

- **Advanced Techniques and Continuous Improvement:**
  - **Finding:** Advanced statistical techniques and machine learning can uncover hidden patterns and correlations.
  - **Recommendation:** Use these techniques along with predictive simulations to test new safety measures and continuously enhance ship design and emergency procedures.

## Conclusion
This project provided crucial insights into the factors affecting survival rates on the Titanic. Understanding these factors allows for the design of ships that offer equitable safety provisions for all passengers, regardless of class or age. The findings serve as a foundation for continuous improvements in maritime safety, aiming to prevent future tragedies.
