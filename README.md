🛡️ CSE Vulnerability Risk Indicator Tool (Standalone Demo)

This repository hosts the offline, standalone Windows version of the CSE Vulnerability Risk Indicator (CSE-VRI).
The tool is designed for use by Designated Safeguarding Leads (DSLs) and authorised safeguarding staff working in schools.
It supports structured CSE risk assessment, record-keeping, and review, with a particular focus on online-to-offline exploitation risk. The app runs entirely locally and does not require internet access, installation, or administrator permissions.

📦 What’s included:

A fully self-contained Windows standalone app. 
Portable R runtime is bundled with the app (no installation required).
The app produces a structured CSE risk assessment form with weighted indicators.
A safeguarding advice engine is linked to selected indicators.
Word report and Action Plan generation is a feature of the app.
Local, cumulative assessment logging helps generate KPI's.
A dashboard is visible showing cohort-level patterns and trends.
A DSL Quick Start guide and Technical README. We have included a cumulative CSV file with ficticious data so you can get used to the features before completing genuine risk assessments. Simply delete our CSV within the 'app' folder and a new CSV will be generated for your school when the first risk assessment is calculated.

🎯 Purpose:

The tool is intended to support frontline safeguarding practice by helping DSLs to:
Identify and record indicators linked to child sexual exploitation, including digital risk.
Combine professional judgement with a consistent, structured scoring framework.
Review previous assessments for individual pupils using UPN.
Build a local picture of emerging patterns across year groups or cohorts.
Generate clear documentation to support safeguarding files, supervision, and referrals.
The tool is designed as decision support. It does not replace professional judgement, statutory guidance, or local safeguarding procedures.
The indicator structure and guidance are informed by current safeguarding practice and align with Keeping Children Safe in Education (KCSIE), CERAF / SERAF, and contemporary research on digital and contextual exploitation.

💻 Download, install and run:

🔽 Step 1: Download

Go to the Releases page:
https://github.com/CSEVRI/vri-demo/releases/latest
Download the latest ZIP file (for example:
CSEVRI_Standalone_Windows_v2.zip)

📂 Step 2: Extract the ZIP

Right-click the ZIP file and select Extract All.
Choose a safe location such as your Desktop or a secure work folder.
Do not run the app directly from inside the ZIP file.

🚀 Step 3: Launch the app

Open the extracted folder.
Double-click Start_App.bat.
A command window will open briefly and the app will launch in your web browser.
If Windows Defender SmartScreen appears:
Click More info.
Select Run anyway.
This is expected for locally run tools.

🌐 Step 4: Using the tool

The app opens in your default browser (Chrome or Edge recommended).
Complete the assessment form and select relevant indicators.
The risk score and band update automatically.
Generate Word reports or Action Plans as needed.
Clear fields before starting the next assessment.
The app runs locally at 127.0.0.1. No data leaves your computer.

📂 Data storage and confidentiality:

All data are stored locally within the app folder.
Cumulative assessments are saved as CSV files.
Reports are generated as Word documents.
No information is uploaded, transmitted, or shared automatically.
Schools remain responsible for managing access, storage, and retention in line with safeguarding and data-protection policies.

🔄 Updating the app:

New versions are released via GitHub Releases.
To update:
Download the latest ZIP from the Releases page.
Extract it to a new folder.
Do not mix files from different versions.
Each release may include updates to indicators, advice content, scoring logic, or dashboard functionality.
Remember to backup your existing CSV file and simply add that to the updated 'app' folder.

🧭 Technical notes:

The application is implemented as an R Shiny app packaged within a portable R environment for offline use.
It runs locally in a web browser but does not require hosting, installation, or internet access.
A separate Technical README is included for IT staff or advanced troubleshooting.

📄 Status and use:

This tool is provided as a demo and trial version for research, evaluation, and safeguarding development purposes.
Feedback from DSLs and safeguarding teams is welcome and helps inform further refinement.
© 2025 David Blackburn, University of Bradford – For educational and safeguarding use only.

For support or feedback, please contact: d.r.blackburn@bradford.ac.uk

