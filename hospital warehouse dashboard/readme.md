🏥 Hospital Emergency Room Dashboard
A Power BI dashboard built to provide analytical insights into the performance of a hospital emergency room for February 2024. This dashboard enables healthcare administrators and analysts to monitor real-time patient metrics, understand operational bottlenecks, and improve service delivery across departments.

📊 Overview
This dashboard visualizes patient-level data collected during emergency room visits. It leverages visual analytics to track:

Patient volume and flow

Admission and referral patterns

Wait times and efficiency

Patient satisfaction scores

Demographic distribution (age, gender, race)

🧠 Business Insights
Here are key insights derived from the dashboard:

✅ Patient Volume and Admission
Total Patients: 431

Admission Rate: 51.97% (224 out of 431)

Slightly more than half of the patients were admitted, indicating a balanced mix of high-acuity and low-acuity cases.

⌛ Wait Time Performance
Average Wait Time: 36.7 minutes

Patients Seen Within 30 Minutes: 65.66%

Efficient triaging, but with room for improvement in reducing wait times further to enhance care delivery.

🙋 Patient Satisfaction
Average Satisfaction Score: 4.72 / 5

High satisfaction levels indicate successful service delivery and good patient-provider interaction.

🧑‍🤝‍🧑 Demographics
Top Age Group: 70–79 (66 patients), followed closely by 40–49 and 30–39

Gender Split:

Female: 54.29%

Male: 45.01%

Not Confirmed: 0.7%

Top Races:

White: 124

African American: 89

Two or More Races: 89

🏥 Department Referrals
Most Referred Departments:

General Practice: 89

Orthopedics: 46

Physiotherapy: 14

Patients Without Referral: 252

Indicates many cases resolved in ER without specialist consultation.

📅 Time & Day Trends
Busiest Day: Thursday (77 patients)

Peak Hour: 17:00–18:00 (16 patients)

Time distribution helps allocate staffing and optimize shift scheduling.

📁 Dataset Description
Column Name	Description
Patient Id	Unique identifier for each patient
Patient Admission Date	Date of ER visit
Patient First Initial	First initial of the patient's first name
Patient Last Name	Patient's last name
Patient Gender	Gender (Male, Female, Not Confirmed)
Patient Age	Age of the patient
Patient Race	Racial or ethnic group
Department Referral	Referred department (if any)
Patient Admission Flag	Boolean (Admitted / Not Admitted)
Patient Satisfaction Score	Score from 1–5 based on feedback
Patient Waittime	Wait time before service (in minutes)
Patients CM	Custom metric (e.g., Case Management indicator)

🛠 Tools & Technologies
Power BI Desktop – Data visualization

Microsoft Excel / CSV – Data preprocessing

GitHub – Version control and collaboration
