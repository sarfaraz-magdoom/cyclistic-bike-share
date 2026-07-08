# 🚲 Cyclistic Bike Share — Case Study

> **Google Data Analytics Professional Certificate | Capstone Project**  
> Presented by **Magdoom Sarfaraz**

> ⚠️ **Note:**To view the output in each of the code line, please use the below as GitHub's built-in preview is not rendering this notebook with the outputs

>[Code Notebook](https://www.kaggle.com/code/magdoomsarfaraz2021/cyclistic-bike-share-case-study)

## 📌 Project Overview

This case study analyzes **Cyclistic**, a fictional bike-share company based in Chicago, as part of the Google Data Analytics Capstone. The goal is to understand how **annual members** and **casual riders** use Cyclistic bikes differently — and to develop data-driven marketing recommendations to convert casual riders into annual members.

---

## 🎯 Business Task

**Key Question:**  
*How do annual members and casual riders use Cyclistic bikes differently?*

**Objective:**  
Use historical bike trip data to identify behavioral trends, and provide actionable insights to help the marketing team design a targeted conversion strategy.

---

## 🗂️ Dataset

- **Source:** [Divvy Bikes Public Data](https://divvy-tripdata.s3.amazonaws.com/index.html)
- **License:** [Data License Agreement](https://ride.divvybikes.com/data-license-agreement)
- **Period Covered:** 12 months of trip data
- **Records:** Millions of ride entries including start/end times, station names, coordinates, and rider type

> ⚠️ *Note: Data has been anonymized — no personally identifiable information is included.*

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **R / R Markdown** | Data cleaning, analysis, visualization |
| `tidyverse` | Data manipulation |
| `ggplot2` | Data visualization |
| `lubridate` | Date/time handling |
| `dplyr` | Data transformation |
| **Kaggle** | Notebook environment |

---

## 📊 Analysis Process

Following the 6 phases of the data analysis process:

1. **Ask** — Defined the business problem and key stakeholder questions
2. **Prepare** — Downloaded, organized, and assessed the raw data
3. **Process** — Cleaned data: removed nulls, fixed formats, filtered outliers
4. **Analyze** — Identified trends by rider type, time, day, and station
5. **Share** — Created visualizations to communicate findings
6. **Act** — Developed top 3 marketing recommendations

---

## 🔍 Key Findings

- 📅 **Casual riders** peak on **weekends**, while **members** ride consistently on **weekdays**
- ⏱️ Casual riders take **longer trips** on average; members take **shorter, frequent trips**
- 🗺️ Casual riders favor **tourist and lakefront stations**; members use **commuter routes**
- ☀️ Casual ridership spikes in **summer months** (June–August)

---

## 💡 Recommendations

1. **Weekend & seasonal promotions** — Target casual riders with membership offers during peak summer weekends
2. **Station-based campaigns** — Place marketing at high-traffic casual rider stations
3. **Ride duration incentives** — Offer perks for members who take longer rides to attract casual converters

## Detailed Recommendations can be found below

About 75% of Cyclistic's total number of rides in a year come from the six month period of May - October. The marketing team at cyclistic should run promotions during this period of the year to:

1, Enhance chances to convert casual customers into annual customers.
2, Use seasonal campaigns to increase margins.
3, Increase visibility among your customers.

There are about 1.45 million casual users and about 2.1 million member users. Recurring billing through annual memberships offers predictable revenue, hence the company is rightly focussed towards maximizing member users. For this purpose, the company can introduce an easy, customizable and flexible subscription model with deals, discounts, or promotions for new members.

The casual users have an average ride length of about 35 minutes which is 2x that of a member user. The company should look for ways for promoting more shorter bike rides. A user with frequent short bike rides is likely to get annual subscription. For this purpose, the company can introduce awareness campaigns like "The Benefits of Going Short" for explaining the benefits of shorter bike rides to the general public and its existing casual customers.

---

## 📁 Repository Structure

cyclistic-bike-share/
│
├── cyclistic-bike-share-case-study.ipynb   # Main analysis notebook
└── README.md                                # Project documentation



## 🔗 Links

- 📓 [Kaggle Notebook](https://www.kaggle.com/code/magdoomsarfaraz2021/cyclistic-bike-share-case-study)
- 🎓 [Google Data Analytics Professional Certificate](https://www.credly.com/earner/earned/badge/b6f73d8c-0ed2-48dd-8fa4-b8352303234a)
- 🐱 [GitHub Repo](https://github.com/sarfaraz-magdoom/cyclistic-bike-share)

---

## 👤 Author

**Magdoom Sarfaraz**
BI Analyst @ Expedia Group via Concentrix | Google Data Analytics Professional Certificate

---

*This project was completed as part of the Google Data Analytics Professional Certificate program.*
