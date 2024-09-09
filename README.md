# Emergency RoomD ashboard

This dashboard provides a comprehensive analysis of emergency room (ER) visits, utilizing data extracted from the "Hospital ER.csv" dataset. The dashboard is designed to offer insights into patient demographics, ER wait times, patient satisfaction, and department referrals, allowing hospital administrators and healthcare professionals to monitor and improve ER operations.

### Dashboard Link
Access the dashboard [here](https://public.tableau.com/app/profile/vanessa.okosun/viz/EmergencyRoomVisitsDashboard_16963796134540/Dashboard1).
![Image of the dashboard](https://github.com/thevannyfiles/Emergency-Room-Dashboard/blob/main/Dashboard%201.png)

### Dataset Description
The dataset used for this dashboard contains detailed information on ER visits, including patient demographics, visit details, and outcomes. Below is a summary of the key columns in the dataset:

* ****date:**** The date and time of the ER visit.
* ****patient_id:**** A unique identifier for each patient.
* ****patient_gender:**** The gender of the patient (e.g., Male, Female).
* ****patient_age:**** The age of the patient.
* ****patient_sat_score:**** The patient satisfaction score, ranging from 1 to 10.
* ****patient_first_initial:**** The first initial of the patient's first name.
* ****patient_last_name:**** The last name of the patient.
* ****patient_race:**** The race or ethnicity of the patient.
* ****patient_admin_flag:**** A boolean value indicating whether the patient was admitted (True) or not (False).
* ****patient_waittime:**** The wait time in minutes before the patient was seen by a healthcare provider.
* ****department_referral:**** The department to which the patient was referred after the ER visit.

### Key Insights and Visualizations
1. ****Patient Demographics:**** Analyze the distribution of patients by age, gender, and race to understand the demographic makeup of ER visitors.

2. ****ER Wait Times:**** Visualize the average wait times across different patient demographics and track how these wait times vary over time.

3. ****Patient Satisfaction:**** Examine the patient satisfaction scores in relation to wait times and other variables, identifying areas where service can be improved.

4. ****Admission Rates:**** Determine the proportion of patients who were admitted to the hospital from the ER, with a breakdown by demographic groups.

5. ****Department Referrals:**** Explore the referrals to different hospital departments, identifying which departments handle the most cases post-ER visit.

### Usage Instructions
1. ****Filtering:**** Use the filters provided on the dashboard to narrow down the data by specific time frames, patient demographics, or other relevant factors.
2. ****Interactivity:**** Hover over data points to view detailed information and click on charts to drill down into specific data segments.
3. ****Exporting:**** The dashboard allows for the export of visualizations and data in various formats for further analysis.

### Technical Details
* ****Tools Used:**** Tableau was used to create the visualizations and interactive elements of this dashboard.
* ****Data Processing:**** Data preprocessing was carried out using Excel to clean and format the dataset before importing it into Tableau.

### Future Enhancements
* ****Predictive Analytics:**** Incorporating predictive models to forecast ER visit trends based on historical data.
* ****Real-Time Data Integration:**** Upgrading the dashboard to include real-time data updates for continuous monitoring.
