# colten-portfolio
Portfolio of projects and experience


# Colten Hodgkin — Project Portfolio

Data Science student focused on applied analytics, telemetry systems, SQL databases, automation, and motorsports performance analysis.

This portfolio highlights selected projects from school, independent development, and real-world work with karting operations. Some projects are summarized with screenshots, diagrams, and explanations rather than full source code because portions are experimental, proprietary, or still being actively developed.

---

## Featured Projects

### 1. Velometrics — Motorsports Telemetry & Speed Mapping

**Project Type:** Independent / Applied Data Science Project

**Focus Areas:** Telemetry analytics, speed mapping, lap comparison, performance visualization

**Technologies:** Python, Pandas, Matplotlib, SQL / SQLite, data visualization

#### Overview

Velometrics is an independent telemetry analytics project focused on creating speed maps and performance insights for karting and other motorsports applications. The project analyzes lap data to help visualize where drivers gain or lose time across a track.

#### Key Features

* Speed map generation using GPS / telemetry-style data
* Lap comparison and fastest-lap reference visualization
* Sector-based performance analysis
* Delta-time comparison between laps, drivers, or karts
* Exploration of driver feedback and AI-assisted coaching concepts

#### What I Built / Worked On

* Designed early telemetry workflows for processing lap data
* Created visual speed maps to show performance across different track sections
* Built analysis concepts for comparing karts, drivers, and sectors
* Developed the project while learning more about telemetry, data visualization, and motorsports analytics

#### Lessons Learned

* How to transform raw movement/performance data into usable visual insights
* How motorsports analytics depends on clean data, context, and repeatability
* How early prototypes can evolve into more structured analytics systems over time

#### Future Improvements

* Interactive live-time Plotly dashboard
* Improved lap alignment and sector filtering
* Cloud-hosted database and web dashboard vailable for users
* Live-time feedback system for drivers/engineers
* More polished data pipeline and documentation

---

### 2. Rush Hour Karting — Database & Web App Concept

**Project Type:** Real-World Operational / Internal Tooling Project

**Focus Areas:** Database design, operational tracking, web application planning, karting workflows

**Technologies:** SQL, Python, web app concepts, database design, streamlit

#### Overview

This project focuses on organizing and improving operational data workflows for Rush Hour Karting. The goal was to create a more structured way to track kart-related information, maintenance needs, and potentially telemetry/performance data.

#### Key Features / Concepts

* Kart and parts data organization
* Maintenance and repair tracking concepts
* Database-backed workflow for operational information
* Potential integration with telemetry and analytics systems
* Web-app structure for easier staff interaction

#### What I Built / Worked On

* Designed database concepts around real karting operations
* Considered how track staff and mechanics would interact with the system
* Connected practical mechanical workflows with data organization needs
* Explored how operational data could support better decision-making and maintenance planning

#### Schema

```
project-root/
├── app.py
├── .streamlit/
│   └── config.toml
├── backups/
│   ├── backup_check.txt
│   └── temp.txt
├── data/
│   └── db.txt
├── database/
│   ├── fix.py
│   ├── init_db.py
│   └── schema.sql
└── modules/
    ├── db.py
    ├── forgot_password.py
    ├── inventory.py
    ├── karts.py
    └── service_logs.py

```

#### Lessons Learned

* How database structure needs to match real operational workflows
* How users interact with tools differently than developers expect
* How mechanical systems, inventory, maintenance, and analytics can connect through data
* How to build predictors off of real-time inputs to warn of trends and future risks

#### Future Improvements

* Improve database normalization and reporting
* Build a cleaner user interface
* Add dashboards for maintenance trends and downtime
* Integrate telemetry outputs with kart records

---

### 3. Capstone Project — Predicting S&P 500 Returns with Macro Variables, Sentiment, and Boosting Models

**Project Type:** Academic Capstone

**Focus Areas:** Exploratory data analysis, predictive modeling, methodology comparison, data visualization

**Technologies:** Python, Pandas, Scikit-learn, data visualization tools, statistical analysis

#### Overview

This capstone project investigated the connections between Macro-Economic Variables and Investor Sentiment with S&P 500 short term returns. The project involved cleaning and analyzing data, comparing variables, testing modeling approaches, and presenting findings through visualizations and a final presentation.

#### Research Question

> Can a combination of public access macro-economic variables and investor sentiment be used as a reliable predictor of short term S&P 500 returns. 

#### Methodology

* Performed exploratory data analysis to understand trends and variable relationships
* Compared short-term and long-term results across selected variables
* Used correlation analysis and variable comparison to evaluate relationships
* Applied machine learning / boosting methods as part of the modeling process
* Discussed methodology challenges related to noisy real-world data and model interpretation

#### What I Contributed

* I aided with creation of the methodology and the formulas used. As a group, we spent many attempts to maximize results, the best results were used in the final project, I contributed to at least 40-50% of the methods and formulas used in this process.
* I helped with cleaning and normalizing of the data once it was collected. I also did a lot of the usage of data when it came to using numpy and pandas to make graphs and charts to show our findings. 

#### Screenshots / Outputs

<img width="266" height="89" alt="image" src="https://github.com/user-attachments/assets/f3f11e90-fca0-432a-93f5-d37e423d31e0" />

<img width="254" height="157" alt="image" src="https://github.com/user-attachments/assets/50b7abed-e804-4e49-9c38-7c3f8ac2d330" />

<img width="227" height="75" alt="image" src="https://github.com/user-attachments/assets/d04d2d15-9540-425c-a313-9a14bfda416c" />

<img width="235" height="141" alt="image" src="https://github.com/user-attachments/assets/218d49e6-6d19-487a-bbbd-a6b89a2c8272" />

<img width="253" height="197" alt="image" src="https://github.com/user-attachments/assets/0d5de9e0-ed45-484c-ab18-ec87a135ce00" />

```

#### Key Takeaways

* Using boosting methods, and with the correct windows of time length used, crude oil shows a small, but significant, inverse relationship to 5 day S&P 500 returns. Other than this, Macro-Economic variables and Investor Sentiment, even when combined in different percentages or mixtures, are not able to be a reliable predictor of S&P 500 returns. 
* Macro-Economic variables when combined have too much inherent noise to be certain as a short term predictor, even with advanced methods. Investor Sentiment is an inherently flawed data source when attempting to use as a predictor because it naturally follows the market and "overreacts" as well documented by other researchers on the topic. 
* Trying different formulas, combinations of data, and methods to predict something specific while using specific data cannot work no matter the effort put forth if the data cannot be used for that specific purpose.

#### Future Improvements

* Improve model validation
* Expand dataset size or variable coverage
* Explore additional modeling approaches
* Build a dashboard or reproducible notebook workflow

---

## Technical Skills Demonstrated

* Python data analysis
* SQL database design
* SQLite / MySQL fundamentals
* Exploratory data analysis
* Data visualization
* Motorsports telemetry concepts
* Machine learning fundamentals
* Web application planning
* Automation concepts
* AWS / cloud fundamentals
* Linux and Ansible fundamentals

## About Me

I am a Data Science student at Arizona State University with interests in data analytics, motorsports telemetry, SQL databases, automation, and applied machine learning. I enjoy building practical tools that connect technical systems with real-world operations.

---

## Contact

**Email:** [clhodgkin@gmail.com](mailto:clhodgkin@gmail.com)
**GitHub:** [Insert GitHub URL]
**LinkedIn:** [Insert LinkedIn URL]
