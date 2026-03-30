# Ohio_Cannabis_Moratorium_Dashboard

An interactive Looker Studio dashboard tracking municipalities and townships in Ohio that have enacted bans or temporary moratoriums on adult-use cannabis operators.

## 🚀 Live Interactive Tracker
[![Live Demo](https://img.shields.io/badge/View_Ohio_Moratorium_Map-d32f2f?style=for-the-badge&logo=googlelookerstudio&logoColor=white)](https://verymaryveryjane.github.io/Ohio_Cannabis_Moratorium_Dashboard/)

---

## 🧐 Why this project?
Following the passage of Issue 2, many local governments in Ohio exercised their right to opt-out or pause business operations. This tool helps stakeholders visualize the regulatory landscape in real-time.

## 🧪 Data Methodology & Sources
Tracking local "opt-outs" and moratoriums in Ohio requires synthesizing data from multiple state and local government channels.

## Data Sources
1. The Ohio Division of Cannabis Control (DCC): Primary source for identifying licensed dual-use operators and state-level regulatory updates.

2. OSU Moritz College of Law (Drug Enforcement and Policy Center): Used for verifying the list of the 149+ Ohio municipal corporations and townships that have enacted moratoriums.

3. Local Government Records: Individual city council and township trustee meeting minutes were cross-referenced to determine the specific "Ending Date" or "Indefinite" status of local bans.

### 🧪 Data Pipeline
* **Extraction:** Manual and semi-automated collection from the Ohio DCC and OSU Moritz College of Law.
* **Cleaning:** Standardized municipality names and geocoded locations for mapping.
* **Visualization:** Connected to Google Looker Studio for a real-time, interactive geospatial view.
