Cyclistic Bike-Share Analysis
Google Data Analytics Professional Certificate – Capstone Project

Status
- Phase 1: Completed
- Phase 2: Completed
- Phase 3: Completed
- Phase 4: Completed
- Phase 5: Completed
- Phase 6: In Progress

Description
This project analyzes 12 months of bike trip data to identify differences between casual riders and annual members, with the goal of recommending strategies to increase memberships.

Tools Used
- Excel
- SQL / Python
- Power BI / Tableau

About the Dataset
The dataset is provided by Divvy (Chicago’s bike-share program) and contains anonymized trip-level data, including ride type, timestamps, stations, and user type.

Phase Summaries

Phase 1 – Ask
- Defined business problem and project objectives.
- Identified stakeholders and key questions.

Phase 2 – Prepare
- Gathered 12 months of trip data from Divvy’s open data portal.
- Checked data credibility, privacy, and accuracy.

Phase 3 – Process
- Removed missing values (`start_station_name`, `end_station_name`).
- Removed duplicates and invalid trip durations.
- Converted `started_at` and `ended_at` to datetime format.
- Calculated `ride_length` and extracted `day_of_week`.
- Saved a 500-row sample for sharing: [`data_cleaned/cyclistic_cleaned_sample.csv`](data_cleaned/cyclistic_cleaned_sample.csv)  
  (Full cleaned dataset stored locally — available upon request.)

Phase 4 – Analyze
- Performed descriptive statistics.
- Calculated average ride duration by user type.
- Analyzed monthly ride trends and day-of-week usage patterns.

Phase 5 – Share
- Created visualizations in Python (Matplotlib, Seaborn):
  - Ride duration by user type (boxplot)
  - Monthly ride trends (line chart)
  - Day-of-week usage (bar chart)
- Saved visual files to `visuals/`.
- Designed optional interactive dashboard in Power BI/Tableau for stakeholder presentation.

Project Documents
- [Phase 1 – Ask](docs/phase1_ask.docx)
- [Phase 2 – Prepare](docs/phase2_prepare.docx)
- [Phase 3 – Process](docs/phase3_process.docx)
- [Phase 4 – Analyze](docs/phase4_analyze.docx)
- [Phase 5 – Share](docs/phase5_share.docx)

Planned Deliverables
- Data Cleaning & Preparation ✅
- Descriptive Analysis ✅
- Visualizations & Dashboards ✅
- Final Report with Recommendations (Phase 6)
