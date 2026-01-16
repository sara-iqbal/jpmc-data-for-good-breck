# Data for Good: Optimising Digital Safety with the Breck Foundation 🛡️

![Status](https://img.shields.io/badge/Status-Completed-green)
![Event](https://img.shields.io/badge/Event-J.P._Morgan_Data_for_Good-blue)
![Tech](https://img.shields.io/badge/Tools-Python%20%7C%20NLP%20%7C%20Geospatial%20Analysis-orange)

## Project Overview
During the **J.P. Morgan Data for Good Hackathon**, I had the privilege of working with **Team 9** to support the **Breck Foundation**, a charity dedicated to protecting young people from online grooming and exploitation.

Our mission was to move beyond simple reporting and use data to drive strategy. We analyzed workshop feedback and external cyber safety trends to help the Foundation identify gaps in their data collection and target their life-saving education where it is needed most.

*You can view the full presentation slides in the `jp_morgan_pdf_of_ppt.pdf` file included in this repository.*

---

## The Challenge
The Breck Foundation does incredible work, but they faced a key challenge: **How do we measure impact and decide where to go next?**

Our team was tasked with:
1.  Analyzing workshop data to assess student knowledge and behavioral changes.
2.  Identifying critical gaps in how data is currently collected.
3.  Comparing internal data against global cyber safety trends.
4.  Proposing data-driven strategies to reach high-risk demographics.

---

##  My Technical Approach
As a core contributor to the team, I focused heavily on **Exploratory Data Analysis (EDA)** and **Natural Language Processing (NLP)** to turn raw survey data into actionable insights.

### 1. Deep-Dive EDA & "The Guardian Gap"
We didn't just look at attendance numbers; we looked for the *story* behind the data. By comparing the Foundation's internal data with external datasets (2020 vs. 2023), we discovered a critical trend we called **"The Guardian Gap."**

* **The Insight:** While daily internet use for 10-15 year-olds has risen significantly, the number of children telling their parents about online risks has dropped.
* **The Impact:** This identified a specific disconnect that the Foundation needs to bridge: empowering children to speak up at home.

**<img width="1110" height="710" alt="image" src="https://github.com/user-attachments/assets/cb19ae1a-619f-45d2-8bb5-fae308e62a46" />
**
*Figure 1: Analysis showing the widening gap between internet usage and parental communication.*

### 2. Natural Language Processing (NLP) on Feedback
To understand what makes a workshop effective, I performed **Semantic Analysis** on the qualitative feedback from students.
* **Technique:** Used NLP techniques to categorize thousands of open-ended responses.
* **Finding:** We identified that "Peer Delivery" and the "Breck Story" were the strongest positive drivers of engagement.
* **Outcome:** We recommended the charity expand their Youth Ambassador program to leverage this peer-to-peer influence.

**<img width="856" height="553" alt="image" src="https://github.com/user-attachments/assets/048485a6-66ac-48ef-ba71-9de853c0e436" />
**
*Figure 2: Frequency analysis of student feedback themes.*

### 3. Geospatial Analysis: The School Opportunity Finder
To help the charity allocate resources efficiently, we built an interactive **Heatmap & Opportunity Finder**.
* **The Tool:** We mapped schools the Foundation has visited (Green) against unvisited schools (Red) that have high deprivation scores (Free School Meal percentage).
* **The Goal:** This allows the charity to proactively target underprivileged areas that are statistically at higher risk but currently underserved.

**<img width="647" height="802" alt="image" src="https://github.com/user-attachments/assets/fde00846-463b-4b89-bf8e-8c7de9847186" />
**
*Figure 3: Geospatial analysis highlighting high-need, unvisited schools.*

---

##  Tech Stack & Tools
This project relied on a robust Python ecosystem:
* **Data Manipulation:** `Pandas`, `NumPy` for cleaning and structuring complex survey data.
* **Visualization:** `Matplotlib`, `Seaborn` for trend analysis and static charts.
* **NLP:** `NLTK`, `Spacy` (or specific library used) for sentiment and text analysis.
* **Geospatial:** `Folium` / `Plotly` for creating the interactive UK school heatmap.

---

##  Key Recommendations
Based on our code and analysis, we delivered a 4-step strategy to the Breck Foundation:
1.  **Save Time:** Automate workshop scheduling using the new dashboard insights.
2.  **Optimise Delivery:** Prioritize "Red Zone" schools (high deprivation, unvisited).
3.  **Targeted Reach:** Shift focus to engage parents and teachers, as our data showed their participation lag behind students.
4.  **Amplify Awareness:** Update curriculum to specifically address the "Guardian Gap" and encourage open dialogue at home.

---

##  Project Structure
* `jp_morgan_pdf_of_ppt.pdf`: The final presentation deck delivered to the judges.
* `/code`: (Optional) Analysis notebooks and scripts used during the hackathon.

---

*Disclaimer: This project was created for the J.P. Morgan Data for Good Hackathon. All data used was anonymized or publicly available to ensure privacy and safety.*
