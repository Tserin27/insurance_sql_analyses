# ANALYSES ON INSURANCE RATE AFFECTING MULTIPLE FACTORS 

-- OBJECTIVE 

The project objective is to analyze insurance premium variations based on key factors such as smoking status, age, BMI classifications, gender, and regional influences. The analysis aims to:

Identify correlations between health risk factors (smoking, BMI, age) and premium costs.

Examine regional differences in pricing based on demographic trends.

Assess gender-based pricing disparities, particularly in underweight categories.

Understand how high-risk BMI classifications impact insurance costs across different age groups.

Evaluate seasonal and market trends affecting premium adjustments.

DASHBOARD

<img width="953" alt="image" src="https://github.com/user-attachments/assets/87e500fa-d970-4790-aa9c-bbc2fff66245" />

ANALYSES ON AVERAGE CHARGES IN RELATION TO SMOKING AND AGE GROUP 

Average insurance charges demonstrate a strong correlation with smoking status, as smokers consistently pay significantly higher premiums compared to non-smokers. This disparity is driven by the well-documented health risks associated with smoking, including respiratory diseases, cardiovascular conditions, and other chronic illnesses, which lead insurers to classify smokers as high-risk policyholders.

Additionally, insurance costs increase with age, with premiums peaking in the 51–65 age group, while the 18–30 age group enjoys the lowest rates. As individuals age, their likelihood of developing medical conditions rises, necessitating higher coverage costs for insurers. This age-based pricing structure reflects the increased probability of claims and the overall impact of aging on health.

Together, these factors highlight the importance of risk assessment in determining insurance premiums, where smoking and aging play a crucial role in shaping pricing models.

<img width="629" alt="image" src="https://github.com/user-attachments/assets/108204d5-5d1c-4e0f-9260-4ccdab081257" />

ANALYSES ON AVERAGE INSURANCE IN DIFFERENT WEIGHT CLASSIFICATION 

nsurance premiums are strongly influenced by BMI classifications, with morbidly obese individuals (BMI >40) paying the highest premiums—especially those aged 51–65, while the 31–40 group experiences the lowest costs within this category.

Weight-Based Trends Across Age Groups:

Obesity, Overweight, and Normal Weight: Premiums consistently increase with age, with 51–65 paying the most and 18–30 paying the least.

Underweight Group: Anomaly observed—31–40 pays the highest premium, whereas 18–30 pays the lowest, possibly due to health risks associated with lower BMI in middle age.

Overall Observations:

Morbidly obese individuals consistently pay the highest premiums across all age groups, reflecting heightened health risks.

Normal and overweight insurers pay comparable premiums, indicating a minimal distinction in risk assessment.

Underweight individuals pay the least, while Male and female insurers generally pay similar premiums, except for underweight females aged 31–40,

<img width="632" alt="image" src="https://github.com/user-attachments/assets/86ea7dad-71ca-446f-97e1-7824007dc644" />

ANALYSES ON Regional Insurance Premium Trends by Gender & Smoking Status:

Female Insurers:

Non-Smokers: The highest premiums are observed in the Northeast, while the lowest are in the Southwest.

Smokers: A contrasting trend—Northeast sees the lowest premiums, whereas the Southeast records the highest costs.

Male Insurers:

Non-Smokers: Similar trends apply, with Northeast insurers paying the highest premiums, while the Southeast and Southwest offer the lowest rates.

Smokers: The Northwest region has the lowest premiums, with Northeast premiums remaining comparable, while the Southeast sees the highest rates.

<img width="712" alt="image" src="https://github.com/user-attachments/assets/2f3d7073-9e67-4d2e-a3ee-9a650a808d67" />

QUERIES FOR SQL 

-- 1.CREATE A DETAIL INFORMATION AND CREAT A CLASS EACH INSURER BASE ON BMI AND AGE GROUP?

-- 2.WHAT ARE THE AVG_CHARGES AND AVG_BMI BASED ON AGE GROUP?

-- 3.WHAT ARE THE AVG_CHARGES AS PER GENDER BASED ON SMOKING AND BMI GROUP?

-- 4.WHAT ARE THE DATA OF AVG_CHARGES BASED ON BMI AND GENDER IN AGE_GROUP BETWEEN (18 TO 30) (31 TO 40) (41 TO 50) AND (51 TO 65)?

-- 5.WHAR IS THE REGION WISE AVG_CHARGES BASED ON GENDER?

-- 6.CREATE A GENDER SEGMENTATION BY WEIGHT_CLASS AND OVERALL AVG_CHARGES

-- 7.WHAT ARE THE PERCENTAGE OF GENDER PAYING MORE THEN AVG_CHARGES ?

-- 8 WHAT ARE THE PERCENTAGE OF GENDER PAYING MORE THEN AVG_CHARGES OF MALE AND FEMALE CONSIDERING SMOKING FACTORS?

-- 9.CREATE PROCEDURE FOR FINDING REGION WISE DATA ON AVG_CHARGES BASE ON GENDER

-- 10.CREATE PROCEDURE FOR FINDING DATA BASE ON BMI GROUP (UNDER_WEIGHT, NORMAL_WEIGHT, OVER_WEIGHT, OBESITY AND MORBID_OBESITY)

-- 11.CREATE PROCEDURE FOR FIDING DATA BASE ON INPUT OF GENDER, BMI_GROUP
