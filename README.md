# INTO University Live Brief Project
#### The goal of this project was to identify and justify a list of the top twenty institutions that INTO University should partner with to increase their reach within the US market. ####

Before constructing a suitable list for potential partners, criteria had to be met to maximise geographical growth and international presence. Institutions were to be located in a state:

* which is proven to be highly attractive to international students
* where INTO does not currently have a university partner (you can find the universities INTO has already partnered with here)
* with a relatively affordable price point for undergraduate study

Based on INTO's preference of receruting international students at scale, KPIs were based on:

1) International Proportion (IP)
2) Average Cost of Attendance
3) Median Household Income

*please see the glossary in the [business case](https://github.com/marofrahman/INTO-university-live-brief/files/11599348/INTO-University_Business_Case.pdf) for more details*

Below is a breakdown of the live brief project includes the **deliverables**:

### 1) Preparation

As a part of this project the [IPEDS](https://nces.ed.gov/ipeds/use-the-data/download-access-database) and [CollegeScorecard](https://collegescorecard.ed.gov/data/) databases. This stage involed cleaning and reforming the data to ensure it could be used for proper data analysis before joining relevant tables and sets together using BigQuery. A [final spreadsheet](https://github.com/marofrahman/INTO-university-live-brief/files/11599480/FullUni_Data.csv) was constructed which contained the entire data set condensed into one page (further code is provided within the attatched files).

### 2) Analysis

The majority of the analysis was performed using a combination of Excel, SQL and GPT. [BigQuery code](https://console.cloud.google.com/bigquery?authuser=1&project=prism-2023-c1&ws=!1m5!1m4!1m3!1sprism-2023-c1!2sbquxjob_635e0d71_18867cf3d8b!3sUS) ultimately built a table that displayed the top 20 suitable universities to partner with.

### 3) Visualisations

To visualise the analysis, a [Power BI dashboard](https://app.powerbi.com/groups/d4794dbe-058d-46e0-a484-5e379b4d31a7/reports/06c2c74e-0121-42bc-8f03-8056297ccb8c/ReportSection?experience=power-bi) was made. Elements of comparison between KPIs and changes overtime were displayed to gather a sense of attendance costs VS household incomes as well as the international presence of these chosen universities. 

### 4) Business Case

The [business case](https://github.com/marofrahman/INTO-university-live-brief/files/11599771/INTO-University_Business_Case.pdf) document contains the executive summary as well as highlights, recommendations and a conclusion. You can find the chosen list of universities within it.

### 5) Powerpoint Slides

As a part of this live brief project, a summary [powerpoint presentation](https://github.com/marofrahman/INTO-university-live-brief/files/11599775/INTO-University_Top5Universities.pptx) focusing on the top 5 universities was submitted to [Peter Thompson](https://www.linkedin.com/in/peterthompson78/?originalSubdomain=uk),  a director at INTO University Partnerships.

### 6) Video Presentation

In terms of a final submission a [video presentation](https://drive.google.com/file/d/1tyQLBuUWs5XaEu3SyD0FMko1Ldh7PTv0/view?usp=sharing) (paired with the powerpoint slides) was delivered to board members of INTO University, explaining our data analysis processes for the candidate partners.
