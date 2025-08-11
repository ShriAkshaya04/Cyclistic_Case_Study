Cyclistic Bike-Share Analysis
Google Data Analytics Professional Certificate – Capstone Project

Status
- Phase 1: Completed
- Phase 2: Completed
- Phase 3: Completed
- Phase 4: Completed
- Phase 5: Completed
- Phase 6: Completed 

Description
This project analyzes 12 months of bike trip data to identify differences between casual riders and annual members, with the goal of recommending strategies to increase memberships.

Tools Used
- Excel
- SQL / Python (pandas, matplotlib, seaborn)
- Power BI / Tableau

About the Dataset
The dataset is provided by Divvy (Chicago’s bike-share program) and contains anonymized trip-level data, including ride type, timestamps, stations, and user type.

Phase 1: Ask
- [Phase 1 Document](docs/Phase1_ASK.docx)
- Defined the business task: Identify how casual riders and annual members use Cyclistic bikes differently.
- Determined stakeholders: Cyclistic marketing team & executives.
- Established success criteria: Provide recommendations to convert casual riders into members.

Phase 2: Prepare
- [Phase 2 Document](docs/Phase2_PREPARE.docx)
- Collected 12 months of historical trip data from Divvy (public dataset).
- Verified licensing and usage permissions.
- Stored raw `.csv` files in `data_raw/`.
- Identified missing values, inconsistencies, and data structure.

Phase 3: Process
- [Phase 3 Document](docs/Phase3_PROCESS.docx)  
Data Cleaning Steps:
- Removed missing values (`start_station_name`, `end_station_name`)
- Removed duplicates
- Converted `started_at` and `ended_at` to datetime
- Calculated `ride_length` and removed invalid durations
- Saved a 500-row sample for sharing: [`data_cleaned/cyclistic_cleaned_sample.csv`](data_cleaned/cyclistic_cleaned_sample.csv)
- Cleaned dataset saved locally for further analysis

Phase 4: Analyze
- [Phase 4 Document](docs/phase4_ANALYZE.docx)  
Analysis Steps:
- Converted date columns and extracted time-based features
- Calculated average ride durations for members vs casual riders
- Analyzed monthly and daily usage patterns
- Generated summary tables for further reporting

Phase 5: Share
- [Phase 5 Document](docs/Phase5_SHARE.docx)
- Created clear, stakeholder-friendly visualizations:
  - Ride duration by user type (boxplot)
  - Monthly ride trends (line chart)
  - Day-of-week usage patterns (bar chart)
- Saved all visuals in `visuals/`
- Designed optional dashboard in Power BI/Tableau

Phase 6: Act
- [Final Recommendations Report](docs/Phase6_ACT.docx)  
Key Recommendations:
1. Promote weekend-to-membership conversions with special discounts for casual riders.
2. Launch seasonal marketing campaigns during peak summer months.
3. Offer trial memberships during high-traffic periods.
4. Highlight exclusive benefits for members in campaigns.

Outputs:
- Final report in `docs/Phase6_Act.docx`
- Updated README.md
- All visuals stored in `visuals/`

 Planned Deliverables
- Data Cleaning & Preparation ✅
- Descriptive Analysis ✅
- Visualizations & Dashboards ✅
- Final Report with Recommendations ✅

