About Dataset:
According to the CDC, heart disease is a leading cause of death for people of most races in the U.S. (African Americans, American Indians and Alaska Natives, and whites). About half of all Americans (47%) have at least 1 of 3 major risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Other key indicators include diabetes status, obesity (high BMI), not getting enough physical activity, or drinking too much alcohol. Identifying and preventing the factors that have the greatest impact on heart disease is very important in healthcare. In turn, developments in computing allow the application of machine learning methods to detect "patterns" in the data that can predict a patient's condition.

The dataset originally comes from the CDC and is a major part of the Behavioral Risk Factor Surveillance System (BRFSS), which conducts annual telephone surveys to collect data on the health status of U.S. residents. As described by the CDC: "Established in 1984 with 15 states, BRFSS now collects data in all 50 states, the District of Columbia, and three U.S. territories. BRFSS completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world.

Variables:
There are 40 variables(columns) in this dataset.

State : The U.S. state where the individual resides.

Sex : Gender of the individual (Male or Female).

GeneralHealth : Self-reported general health status of the individual.

PhysicalHealthDays : Number of days in the past 30 days that physical health was not good.

MentalHealthDays : Number of days in the past 30 days that mental health was not good.

LastCheckupTime : Time since the last routine checkup or health examination.

PhysicalActivities : Frequency of engaging in physical activities or exercises.

SleepHours : Average number of hours of sleep per night.

RemovedTeeth : Number of permanent teeth removed due to dental issues.

HadHeartAttack : Whether the individual has had a heart attack.

HadAngina : Whether the individual has experienced angina (chest pain or discomfort).

HadStroke : Whether the individual has had a stroke.

HadAsthma : Whether the individual has had asthma.

HadSkinCancer : Whether the individual has had skin cancer.

HadCOPD : Whether the individual has had Chronic Obstructive Pulmonary Disease (COPD).

HadDepressiveDisorder : Whether the individual has had a depressive disorder.

HadKidneyDisease : Whether the individual has had kidney disease.

HadArthritis : Whether the individual has had arthritis.

HadDiabetes : Whether the individual has had diabetes.

DeafOrHardOfHearing : Whether the individual is deaf or hard of hearing.

BlindOrVisionDifficulty : Whether the individual has blindness or vision difficulty.

DifficultyConcentrating : Self-reported difficulty in concentrating.

DifficultyWalking : Self-reported difficulty in walking.

DifficultyDressingBathing : Self-reported difficulty in dressing or bathing.

DifficultyErrands : Self-reported difficulty in running errands.

SmokerStatus : Current smoking status of the individual (smoker, former smoker, non-smoker).

ECigaretteUsage : Whether the individual uses e-cigarettes.

ChestScan : Whether the individual has had a chest scan.

RaceEthnicityCategory : Categorized race or ethnicity of the individual.

AgeCategory : Categorized age group of the individual.

HeightInMeters : Height of the individual in meters.

WeightInKilograms : Weight of the individual in kilograms.

BMI : Body Mass Index calculated from height and weight.

AlcoholDrinkers : Whether the individual consumes alcohol.

HIVTesting : Whether the individual has undergone HIV testing.

FluVaxLast12 : Whether the individual received a flu vaccine in the last 12 months.

PneumoVaxEver : Whether the individual has ever received a pneumonia vaccine.

TetanusLast10Tdap : Time since the last tetanus vaccination (in the last 10 years, received Tdap).

HighRiskLastYear : Whether the individual has been considered at high risk for the past year.

CovidPos : Whether the individual tested positive for COVID-19.

Problem Statement:
Understanding and Mitigating Cardiovascular Health Disparities: An In-Depth Analysis of Risk Factors and Health Behaviors in the Adult Population.
The problem centers on identifying and understanding the factors that exert the most significant influence on heart disease prevalence.This exploration is crucial for healthcare initiatives and interventions aimed at prevention and management. The dataset encompasses a range of variables, including demographic information, health behaviors, chronic conditions, and COVID-19 status, providing a rich source for uncovering patterns, correlations, and disparities in cardiovascular health.

We're looking at big questions like what things make heart problems more likely, how mental and physical health are linked, what habits and steps help prevent heart issues, how other health problems affect the heart, and if issues like hearing or vision problems are connected to heart disease. We're also checking how smoking and e-cigarettes are used and how COVID-19 affects heart health.

Our main goal is to extract actionable insights from this wealth of data. We want to make plans that focus on specific things to help reduce differences in heart health and make everyone's heart healthier in the adult population.

Research and Analytical Questions:
These research questions are given by ChatGPT according to our problem statement.

Demographic Variation:

How does the prevalence of heart disease and major risk factors vary across different demographic groups (sex, age, race/ethnicity)? Are there specific subgroups experiencing higher cardiovascular health disparities? Risk Factor Patterns:

What are the common patterns and combinations of major risk factors (high blood pressure, high cholesterol, smoking) within the dataset? How do these patterns relate to the overall cardiovascular health of individuals?

Impact of Chronic Conditions:

Among individuals with chronic conditions (diabetes, asthma, COPD), how does the presence of these conditions correlate with heart disease prevalence?
Are certain chronic conditions more strongly associated with cardiovascular health disparities?
Behavioral Correlations:

Explore the relationships between health behaviors (physical activity, sleep, alcohol consumption) and the prevalence of heart disease.
Identify key behavioral factors that may contribute to cardiovascular health disparities.
Effect of Mental Health on Heart Disease:

Investigate the interplay between mental health (mental health days, depressive disorders) and heart disease.
Are individuals with certain mental health conditions more susceptible to cardiovascular issues?
Sensory Impairments and Cardiovascular Health:

Analyze the impact of sensory impairments (deafness, vision difficulties) on heart disease prevalence and risk factors.
Explore if difficulty in concentration or physical activities differs based on sensory impairments.
Impact of COVID-19:

Explore the influence of COVID-19 on cardiovascular health, considering its association with heart disease prevalence and related risk factors.
Analyze if individuals who tested positive for COVID-19 exhibit distinctive patterns in cardiovascular health.
Some Other questions:

Can you indicate which variables have a significant effect on the likelihood of heart disease?
How many people have at least 1 of 3 major risk factors for heart disease: high blood pressure, high cholesterol, and smoking.
