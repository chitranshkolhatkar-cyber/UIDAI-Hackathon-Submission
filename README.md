# Pulse of the Nation: UIDAI Hackathon Submission 2026

### Project Overview
This project analyzes Aadhaar Enrolment and Update datasets to identify societal trends. By tracking the volume of "Address Updates" and "New Enrolments" at the district level, we created a proxy for monitoring **internal migration** and **economic activity**.

### Key Features
* **Automated Data Ingestion:** Python script (`solution.py`) automatically merges multiple CSV shards (Biometric, Demographic, Enrolment).
* **Geospatial Analysis:** Identifies top districts with high-velocity Aadhaar activity.
* **Visualization:** Generates bar charts to highlight migration corridors.

### Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib, ReportLab (for PDF generation)

### How to Run
1.  Place all UIDAI CSV files in the root folder.
2.  Run `python solution.py`.
3.  Output: `Final_Hackathon_Submission.pdf`.
4.  
