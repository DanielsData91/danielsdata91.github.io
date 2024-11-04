<link rel="stylesheet" href="styles.css">

<img src="images/Data Analytics 2.png"/>

# About me in 10 words!
<h2 class="about-heading">Passionate Data Analyst with a Background in Client-Centered Solutions</h2>

I’m a data analyst with a diverse background, open to relocation. Throughout my career, I’ve developed a strong ability to analyze client needs, create tailored solutions, and deliver insights that drive meaningful change. Now, I’m applying these skills to data analysis, specializing in transforming raw data into actionable insights with tools like Excel, Tableau, SQL, and Python.

I’m passionate about problem-solving and data storytelling, using my creativity to build visualizations that empower organizations to make informed decisions. My unique background allows me to appreciate both the human and analytical aspects of data, providing a holistic approach to solving complex problems.

I’m actively seeking a Junior Data Analyst position where I can contribute to a data-driven team and further develop my expertise in data visualization and analysis.

<details>
  <summary>📃 Resume</summary>
<br>
Experience<br>

Here is a quick overview for you. You can also click the following link to visit my LinkedIn profile for full details about my work history and educational background<br>
<a href="https://www.linkedin.com/in/daniel-müller-profile/">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
</a>
<br><br>
Feel free to download my complete resume from<br>
<a href="https://drive.google.com/file/d/1AyPYACmAiGfu91brKuZabJCuLaJeeMuW/view?usp=drive_link/">
  <img src="https://img.shields.io/badge/googledrive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white"/>
</a>
<br><br>
🧑‍💼 Instructor <br>
📆 April 2020 - December 2023<br>
📍 British Culture Academy, Kawaguchi/Japan
<br><br>
Impact: <br>
Increased class enrollment by 30% within one year, launched 10 new classes, and secured a new school partnership, expanding the Academy’s reach and service offerings.<br><br>

🧑‍💼 Nutrition Coach & Sales <br>
📆 July 2013 - December 2018<br>
📍 Sportstudio vitafit GmbH, Dreieich/Germany
<br><br>
Impact: <br>
Achieved a 70% conversion rate of new walk-in clients and established a specialized nutrition course held three times a year, significantly boosting service offerings and client loyalty.
<br><br>
</details>

<details>
  <summary>📁 Projects</summary>
  
Projects

Here is a quick overview for you. You can also click the following link to visit my GitHub profile for more details about the projects I have done so far: 

<a href="https://danielsdata91.github.io/">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile"/>
</a>
<br><br>

- 👨‍💻 Marketing Analyst<br>
  📆 October 2024<br>
  📍 CareerFoundry - Berlin/Germany<br>
  📁 Project Title: Instacart Basket Analysis<br>
  🧰 SKills:<br>
  <img align="left" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
  <img align="left" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />
  <img align="left" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br><br>

- 👨‍💻 Data Analyst<br>
  📆 September 2024<br>
  📍 CareerFoundry - Berlin/Germany<br>
  📁 Project Title: Rockbuster Stealth Analysis<br>
  🧰 Skills:<br>
  <img align="left" src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" />
  <img align="left" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img align="left" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img align="lreft" src="https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white" />
  <br><br>

</details>
<br>

**From here on you can read trough of my recent projects, the details will show up when clicking the link below the project portfolio image**

---
<h2 class="about-heading">Project Case Study 1: Instacart Basket Analysis</h2>
<br><br>
<img src="images/Collage Case Study Instacart.png"/>

<details>
  <summary>📁 Project Case Study 1: Instacart Basket Analysis - Detailed Overview</summary>
1. Introduction

<h2 class="about-heading">Challenge</h2><br>
Developing marketing strategies based on data gained through initial and exploratory analysis.

The process<br>
Conducting an exploratory analysis in Python to identify differences between classifications of demographic informations and examine possible relationships between customers profiles. Performing basic aggregations to discover the degree of capacity during the day at Instacart.

**The goal**<br>
The goal was to identify the most profitable time frames for placing commercials, and to carve out specific order habits of different customer profiles who the advertisements should be addressed to.

### 2. Step 1: Customer Ordering Habits

Understanding customer ordering patterns is crucial for the client’s targeted marketing efforts. This analysis aimed to clarify customer purchase frequency, peak purchasing times, and popular product preferences. With these insights, the client can strategically time their advertising and focus on promoting high-demand products to maximize engagement and return on marketing investment.

In this phase, I performed descriptive analysis using Python to pinpoint key metrics and assess customer loyalty, specifically by analyzing the intervals between repeat purchases. This enabled us to segment customers based on loyalty and inform more effective marketing strategies.

**Insights**<br>
1: Loyal customers usually return after 8 days. 
2: Most orders are placed between 10 am and 4 pm
3: The busiest days are Sunday and Monday
4: The most popular goods are from the produce department

### 3. Step 2: Customer Profiling

The previous analysis identified general customer ordering habits; however, it’s now essential to pinpoint which customer segments generate the most revenue. This is particularly valuable for tailoring advertisements to target high-value customer profiles effectively.

I conducted an exploratory data analysis and created product labels, assigning them to distinct customer profiles based on key demographics such as age, marital status, and number of dependents. Insights from this analysis revealed that age is the most significant differentiator among high-value customers, providing a critical factor for refining marketing strategies.

**Insights**<br>
Age is the significant differentiator


### 4. Challenges - How did I solve them?

**1: Unexpected NaN Values during Step 1**<br>
While analyzing age groups in relation to order frequency, I encountered unexpected NaN values in the crosstab output. To resolve this, I reviewed and refined the frequency flag definitions in the dataset, which corrected the categorization and provided accurate insights.

**2: Busiest Hours of the Day and Expenditure**<br>
In a separate analysis to identify peak purchasing hours, an initial expenditure-by-hour visualization showed contradictory results. I addressed this by regrouping all orders by hour and recalculating the total expenditure. This adjustment produced a line graph that accurately reflects the busiest hours, offering clearer insights into optimal times for targeted marketing efforts.

### 5. Conclusion and Recommendations

**Customer**<br>
Loyal customers typically return to place a new order approximately every 8 days. While helpful, this insight is less critical compared to optimizing specific marketing strategies for targeted growth.

**Timeing**<br>
Customers place the highest number of orders between 10 am and 4 pm on Sundays and Mondays, making these ideal times for targeted ads to convert regular customers into loyal ones. To further drive sales, I recommend scheduling advertisements during off-peak times—such as early mornings (6 am to 8 am) and evenings (5 pm to 10 pm) on less busy days like Wednesdays and Thursdays. This strategic timing can increase traffic on slower days, balancing demand and enhancing revenue.

**Product**<br>
The produce department is the most popular, with products classified under the Food & Grocery label generating the highest number of orders across diverse customer segments. By focusing ads on these high-demand products, Instacart’s marketing team can increase engagement and drive more consistent sales across all customer profiles.

**Customer Profile**<br>
Married customers, especially those in households with 1-2 dependents, are among the highest purchasers across age groups. Knowing this demographic provides a complete view for the marketing team, allowing them to tailor advertisements effectively by focusing on not only when and what to advertise but also who the core audience should be. This level of targeting can significantly increase the profitability and precision of Instacart’s marketing strategy.

### Access to additional content

Access the Final Report by [clicking here](https://docs.google.com/spreadsheets/d/14rczGgmBJOYZWz8Xh7ZP6FYDQdYgK3tb/edit?usp=drive_link&ouid=102970833740850606782&rtpof=true&sd=true) from my Google Drive.

Access the Python Script Section by [clicking here](https://github.com/DanielsData91/Instacart-Basket-Analysis) from my GitHub Profile.

Access the Project Case Study Files from my Google Drive by [clicking here](https://drive.google.com/file/d/1EoxlccECVwob6XTRJlb8JcdDoxHbz4GC/view?usp=drive_link).
<br><br>
<br><br>

</details>
<br>

<h2 class="about-heading">Project Case Study 2: Rockbuster Stealth - Online Movie Rental Service Analysis</h2>
<br><br>
<img src="images/Collage Case Study Rockbuster.png"/>

### 1. Introduction

**The challenge**<br>
Conduct detailed data analysis to generate actionable insights that support the Business Intelligence team in crafting a strategic launch plan for an online rental service.

**The process**<br>
Utilized PostgreSQL to explore and analyze multiple datasets, executing complex functions to assess sales performance. Applied geospatial analysis to pinpoint high-lifetime-value customers and performed descriptive statistics with targeted filters to identify the most profitable countries and customer segments.

**The goal**<br>
Define potential markets for the online rental service by evaluating sales contributions across countries, analyzing movie genres for performance, and identifying high-lifetime-value customers. These insights informed a data-driven strategy to optimize the service launch and maximize profitability.

### 2. Business Insights and How I identified them

I began with a thorough statistical analysis to determine the top-performing genres and ratings, using aggregated metrics to identify content categories with the highest engagement and revenue potential. By pinpointing these profitable genres, I provided Rockbuster with targeted recommendations for expanding their digital library, focusing on high-demand content that aligns with customer preferences and maximizes potential ROI.

The next step involved analyzing customer geolocation data to identify and prioritize high-value regions. Leveraging advanced grouping and filtering functions in PostgreSQL, I segmented customers based on lifetime value and created a detailed geospatial map in Tableau. This visualization revealed key geographic markets and hotspots for high-lifetime-value customers, equipping Rockbuster with actionable insights into not only what content is in demand but also where to direct targeted marketing efforts for optimized growth.

### 3. Conclusion and Recommendations

**Movie**<br>
Prioritize adding movies with high-demand MPAA ratings (PG-13, PG, R) to the streaming service, and regularly monitor shifts in rating preferences to keep the content library relevant and appealing.

**Location**<br>
Given that Asia contributes 40% of total revenue, maintain targeted marketing efforts to sustain strong performance in this key region. Additionally, invest in marketing initiatives in underperforming regions to increase overall market share and diversify revenue sources.

**Customer**<br>
Launch social media campaigns and loyalty programs, such as lotteries or rewards, for high-LTV countries like Reunion, the USA, Brazil, and top global customers to boost long-term customer value and encourage repeat engagement.

**Online Catalog**<br>
Expand the online catalog with movies from popular genres like Sports, Sci-Fi, and Animation, and prioritize promoting these genres on the website to enhance visibility and drive engagement.

### Access to additional content

Access the SQL Code Section by [clicking here](https://github.com/DanielsData91/Rockbuster-Stealth-Project/tree/main/SQL%20Code) from my GitHub Profile.

Access the Project Case Study Files from my Google Drive by [clicking here](https://drive.google.com/file/d/1V3kQ9nkyfYVaXbztePThmmGVTzqdR1q3/view?usp=drive_link).
<br><br>
<br><br>
<h2 class="about-heading">Project Case Study 3: Preparing for Influenza Season</h2>
<br><br>
<img src="images/Collage Case Study CDC.png"/>

### 1. Introduction

**Problem**<br>
Each year, the USA faces a challenging influenza season with rising infection rates, especially among the growing elderly population. To manage this effectively, staffing agencies must strategically allocate healthcare workers to hospitals in states projected to have the highest influenza-related mortality rates in the coming year.

**Analysis Approach**<br>
Used descriptive analysis to identify the most vulnerable groups and assess the demographic impact of influenza, highlighting high-risk populations.
Mapped geographic regions with the highest mortality rates and identified seasonal patterns in influenza outbreaks to predict peak periods.
Analyzed correlations between mortality rates and vulnerable population segments, enabling precise forecasting for effective resource allocation.

**Targeted Distribution Strategy**<br>
The objective was to pinpoint the U.S. regions most in need of support during the influenza season, ensuring optimal medical staff distribution for maximum impact. By forecasting high-risk areas and vulnerable populations, this approach supports efficient staffing decisions and improved preparedness for the upcoming influenza season.

### 2. Approach - Staff Distribution
**WHO - Individuals over 65 years**<br>
Conducted a descriptive analysis to quantify the composition of influenza-related mortality rates across age groups, revealing that individuals over 65 are most vulnerable—confirming key assumptions for the staffing agency. These findings allow the agency to prioritize resources and tailor staffing levels based on age-related risk

**WHERE - Southern Region of the USA**<br>
By further identifying geographic locations with concentrated populations of vulnerable individuals, by using a geospatial analysis, the agency gains clear, data-backed guidance on where to allocate medical staff for the greatest impact. This insight enables strategic workforce deployment

**WHEN - November - April**<br>
In addition, historical trend analysis of seasonal influenza patterns visualized in a line graph allows the agency to predict peak infection periods. Armed with this predictive insight, the agency can deploy staff ahead of peak times, maximizing readiness and reducing patient overload. Ultimately enhancing the efficiency and effectiveness of its services.

### 3. Conclusion and Recommendations
**Implement a Localized Vaccine Campaign**<br>
Target states with higher death counts among vulnerable groups to maximize immunization efforts. A focused vaccination drive could lower infection rates by approximately 20% in high-risk areas, improving seasonal readiness.

**Launch an Educational Campaign**<br>
Develop presentations and public events to highlight influenza risks and the critical importance of vaccinations, aiming to increase vaccination uptake among vulnerable populations by at least 30%. This initiative can enhance community awareness and reduce seasonal infection rates.

**Conduct a Staff and Patient Survey**<br>
Distribute surveys to gather insights from medical staff and patients regarding their influenza season experiences. Analyzing these responses will inform future staffing models and improve resource allocation strategies, potentially increasing efficiency in staff deployment by 25% based on informed feedback.


### Access to additional content

Access the Dashboard by [clicking here](https://public.tableau.com/shared/YQ6WCNN4P?:display_count=n&:origin=viz_share_link) to visit my Tableau page.

Access the Project Case Study Files from my Google Drive by [clicking here](https://drive.google.com/file/d/1yu3zcjjm7o2ihsS3ddsNmiHr2e7kxUJl/view?usp=drive_link).

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
