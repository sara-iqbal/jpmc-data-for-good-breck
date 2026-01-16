# Optimising Reach & Maximising Impact: Breck Foundation Data Analysis 🛡️

![Status](https://img.shields.io/badge/Status-Completed-green)
![Event](https://img.shields.io/badge/Event-J.P._Morgan_Data_for_Good-blue)
![Tech](https://img.shields.io/badge/Python-Pandas%20|%20NLP%20|%20Geospatial-orange)

##  Project Overview
Developed during the **J.P. Morgan Data for Good Hackathon**, this project aims to support the **Breck Foundation** in their mission to educate young people about online safety and grooming.

[cite_start]Our team (Team 9) analyzed workshop data and external cyber safety trends to identify gaps in data collection, measure workshop effectiveness, and propose strategies to enhance impact[cite: 552, 555].

###  The Challenge
The Breck Foundation challenges participants to:
1.  **Analyze Workshop Data:** Assess the impact of workshops on student knowledge and behavior.
2.  **Identify Gaps:** Evaluate current data collection methods.
3.  **Integrate External Trends:** Compare internal data against global cyber safety risks.
4.  **Optimize Delivery:** Propose data-driven recommendations to target high-need demographics.

## 💡 Key Solution: The School Opportunity Finder
We developed a data-driven approach to prioritize outreach to underprivileged and high-need students who are most at risk but currently under-served.

### 1. Geospatial Heatmap & Opportunity Finder
We created an interactive **School Opportunity Finder** dashboard that maps visited vs. unvisited schools.
* [cite_start]**Green Markers:** Schools already visited by the Foundation[cite: 852].
* [cite_start]**Red Markers:** Unvisited schools flagged as "High Need" based on Free School Meal (FSM) percentages (Deprivation Index)[cite: 852].
* [cite_start]**Outcome:** This allows the charity to strategically allocate resources to areas with the highest deprivation, ensuring targeted life-saving education[cite: 746, 749, 819].

*(Add a screenshot of your Heatmap from Slide 11 here)*

### 2. NLP & Sentiment Analysis
We applied **Natural Language Processing (NLP)** to analyze qualitative feedback from workshops.
* [cite_start]**Top Insights:** "Peer Delivery Effectiveness" and the "Breck Story Impact" were the most frequently cited positive drivers in workshop feedback[cite: 610].
* [cite_start]**Actionable Advice:** We recommended maintaining the authentic storytelling approach while expanding youth-led safety advocacy initiatives[cite: 616, 617].

*(Add a screenshot of your NLP bar chart from Slide 4 here)*

### 3. External Trend Analysis: "The Guardian Gap"
Our analysis of external datasets (2020 vs. 2023) revealed a critical insight we termed **"The Guardian Gap"**:
* [cite_start]While daily internet use among 10-15 year-olds has risen by **3.36%**[cite: 659], the percentage of children telling their parents about online risks has dropped significantly.
* [cite_start]**43.4%** of children tell *no one* if they receive sexual messages[cite: 721].
* [cite_start]**Insight:** As children's exposure peaks, communication lines with parents are breaking down, creating a gap where groomers operate[cite: 704, 705].

## Tech Stack
* **Python:** Core analysis and data manipulation.
* **Pandas/NumPy:** Cleaning and processing workshop attendance and survey data.
* [cite_start]**NLP (NLTK/Spacy):** Semantic analysis of feedback forms to derive behavioral insights[cite: 608].
* [cite_start]**Geospatial Libraries (Folium/Plotly):** Creating the interactive UK heatmap to visualize reach[cite: 818].
* **Data Visualization:** Matplotlib/Seaborn for trend analysis.

##  Recommendations
Based on our findings, we proposed a 4-step strategy for the Breck Foundation:
1.  [cite_start]**Save Time:** Streamline the planning/scheduling of workshops using the dashboard[cite: 557].
2.  [cite_start]**Optimise Delivery:** Prioritize unvisited schools with high deprivation scores (FSM data)[cite: 561, 853].
3.  [cite_start]**Targeted Reach:** Focus on engaging parents and teachers, as our data showed their participation is relatively low compared to students[cite: 569, 573].
4.  [cite_start]**Amplify Awareness:** Bridge "The Guardian Gap" by integrating digital citizenship and emotional resilience content to encourage children to speak up[cite: 648, 704].

## 👥 Contributors
* **Team 9** - J.P. Morgan Data for Good Hackathon

---
*Disclaimer: This project was created for the J.P. Morgan Data for Good Hackathon to support the Breck Foundation. All data used was anonymized or publicly available.*
