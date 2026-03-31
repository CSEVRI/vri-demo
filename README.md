🛡️ Online Harm Risk Assessment Tool (v2.1) with earlier CSE-focused demo (v2.0)

This repository hosts the offline, standalone Windows version of the Online Harm Risk Assessment Tool. The tool is designed for use by Designated Safeguarding Leads (DSLs) and other authorised safeguarding staff working in schools. It supports structured assessment, record-keeping, and review of online harms affecting children and young people, including harms that may overlap with exploitation, coercion, sextortion, grooming, image-based abuse, fraud, and online-to-offline risk.

An earlier CSE-focused demo version is also retained in this repository for developmental and comparison purposes. The current primary version is the Online Harm Risk Assessment Tool v2.1.

The app runs entirely locally and does not require internet access, installation, or administrator permissions.


📦 What’s included:

- A fully self-contained Windows standalone app
- Portable R runtime bundled with the app, with no installation required
- A structured risk assessment form with weighted indicators
- A safeguarding advice engine linked to selected indicators
- Word report and Action Plan generation
- Local cumulative assessment logging to support oversight and review
- A dashboard showing cohort-level patterns and trends
- A DSL Quick Start Guide and Technical README

A cumulative CSV file with fictitious data is included so users can explore the features before completing genuine assessments. If required, simply delete the example CSV within the app folder and a new CSV will be generated when the first assessment is completed.

🎯 Purpose:

The tool is intended to support frontline safeguarding practice by helping DSLs to:

- identify and record indicators linked to online harm
- recognise patterns that may suggest exploitation, coercion, grooming, image-based abuse, or other digitally mediated safeguarding concerns
- combine professional judgement with a consistent structured framework
- review previous assessments for individual pupils using UPN
- build a local picture of emerging patterns across year groups or cohorts
- generate clear documentation to support safeguarding files, supervision, referrals, and multi-agency discussion

The tool is designed as decision support. It does not replace professional judgement, statutory guidance, or local safeguarding procedures. The indicator structure and guidance are informed by current safeguarding practice and align with Keeping Children Safe in Education (KCSIE), CERAF / SERAF, and contemporary research on online harm, exploitation, and contextual safeguarding.


💻 Download, install and run:

🔽 Step 1: Download

Go to the Releases page:
https://github.com/CSEVRI/vri-demo/releases/latest
Download the latest ZIP file (for example:
Online_Harm_Risk_Indicator_Standalone_Windows_v2_1.zip)

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
For educational and safeguarding use only.

For support or feedback, please contact: d.r.blackburn@bradford.ac.uk

