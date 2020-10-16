---
title: "MTL Session Red, Part 1 - Learner See"
author: "Team PSD"
date: "March 2020"
release: "MTL 2.0"
output: 
  github_document: default
  html_document: default
  pdf_document: default
  word_document: default
  ioslides_presentation: default
  slidy_presentation: default
  powerpoint_presentation: default
---

[<img src = "https://github.com/lzim/teampsd/blob/master/resources/logos/mtl_how_red.png"
     height = "175" width = "290">](#DontLink)

# MTL Red Part 1

# Today we're modeling to learn from patient data and team trends.

## Done and Do (15 minutes)
<!-- Do/Done Tables -->
| [<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/done.png" height = "80" width = "80">](#DontLink) **Done** | [<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/do.png" height = "90" width = "90">](#DontLink) **Do** |
| --- | --- |  
| [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/va_team_psd_logo_sq_sm.png" height = "75" width = "100">](mailto:mtl.help@va.gov) [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) We logged in to mtl.how/data to look at the facility data.  [<img src="https://raw.githubusercontent.com/lzim/teampsd/master/resources/gifs/mtl_2.0/data_ui_login.gif" height="200px" width="350px" />](#DontLink)  | [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) We will build our team in the *MTL* Data User Interface and review our team data. [<img src="https://raw.githubusercontent.com/lzim/teampsd/master/resources/gifs/mtl_2.0/session2_data_ui_2.gif" height="200px" width='400px'/>](#DontLink)|  
 
<!-- Learning Objectives Icon --> 
[<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/learning_objectives.png" height = "90" width = "90" style ="display: inline-block"/>](#DontLink) 

## Learning Objectives

1.	Describe the criteria determined to build your team in the *MTL* Data User Interface.

2.	Test your expectations about team historical trends against actual results in the "data", "viz" and "count" tabs.

3.	Apply your clinical expertise to translate learnings from the *MTL* Data UI into team decisions.

# In-session Exercise (30 minutes)

## *MTL* on BISL

### 1. Open an internet browser window. Go to mtl.how/data. First select your VISN and then select your facility.

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/data_ui_login.gif)](#DontLink)


### 2. Explore the facility data.
- To **view facility data** click on the [...] next to the file **"facility.xlsb"** and click **"Edit"** to open in Excel.
- **Team files are in team folders.** If you do not see a team folder, **request a team folder above.**

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/data_ui_splashpage.gif)](#DontLink)

- Click through the tabs on the bottom of the Excel spreadsheet. What options are there and what do they mean? Hints:
  - Data: Sortable report of data
  - Diag: Diagnostic data 
  - Enc: Encounter types of visits
  - HF: Health Factors data related to visits
  - Meas: Measures or flag names
  - Viz: Visualization of trends  

- What filtering options are available? 
  - Filter to your clinic or division to see trends for the last two years.

- vizDiag shows unique visits by primary diagnosis on the visit of PTSD, Dep, OUD, or AUD. 


## Your Team Data Folder

### 3. Scroll to your team folder at the bottom of the page. Open the data_ui folder and open your data_ui file in Excel.
- Click on the 3 dots [...] next to the data_ui file.
- Click on "Edit" to open in Excel, then click "Edit Workbook" at the top of the sheet.

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/edit_in_excel.gif)](#DontLink)

### 4. Go to the ClinicSelection tab. Use columns C-H to select the clinics that make up your team.
- You can sort and filter by Clinic Name, Division Name, Physical Location, Primary Stopcode, Secondary Stopcode, and Default Provider.
- Note: This will pull all clinics used in the last two years (including de-activated clinics: denoted by "ZZ"). For de-activated clinics, you can find the date of de-activation in column I.
- Follow the instructions in **Box A2.** 
- After filtering, click the "Add All" arrow in column B (Cell B6). Fine-tune your selections by double-clicking on the clinic name in column A (to remove) or column C (to add).
- In the future, if you want to quickly get the same list of clinics again, you can select the grey "Get previous clinic list from last click of Get Patient-level Data" arrow in Column B (Cell B3).

### 5. To view your team patient data and your team trends click "Get Patient-level Data." We will not do this in-session today.
- **You already have a fresh data UI file to work with in your team data_ui folder.** 
- We will learn about the "Create Team Data Table" button in our next team meeting.
- **To query patient and clinic level data using the data_ui, you will need LSV permissions.** To check which facilities you have LSV access for, click [here](https://spsites.cdw.va.gov/sites/PBM_AD/_layouts/15/ReportServer/RSViewerPage.aspx?rv%3aRelativeReportUrl=/sites/PBM_AD/AnalyticsReports/LSVAccessVerification.rdl) (VA intranet only).
- **If you don't have access to facilities that you believe you should, please verify:**
   1. CPRS access/permissions at your station (i.e COR tab access for CPRS).
   2. Your network username recorded in VistA.
   To have your network username recording in VistA, please follow the instructions outlined [here](https://vaww.dev.fre.cdw.va.gov/sites/D05_VISN21/DashboardDevelopment/Updating%20Network%20UserName%20in%20VistA.aspx) (VA intranet only). 


### NOTE: It takes some time to run a query from your team data UI to the VA Corporate Data Warehouse. 
- On average (depending on the size of your team) it may take 15 minutes or so for your team data UI to pull in fresh data, and Microsoft Excel will be unresponsive until the data UI has finished pulling in your data.

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/session2_data_ui_2.gif)](#DontLink)

### 6. Click to view the "viz" tab, which show team trends.
- There are team trends for diagnoses, encounters, health factor data (e.g., suicide plans, evidence-based practice templates), and measures from Mental Health Assistant.
  - What stands out to you?
  - What is most important to you to check out first?
  - What is most surprising?

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/session2_data_ui_4_viz_diag.gif)](#DontLink)

- Click on any trend line and then "Quick Explore" (look for the magnifying glass). In the "Explore" box, pick the item you want to explore and click "Drill To." Keep using the Quick Explore to drill until you reach the data you want. 
  -To return to the original settings, click on the gray "Reset Pivot Chart."
  - The viz tabs will also return to default selections, when you click "Get Patient-level Data" for new data pulls.

- Right click on a trend line and filter to hide a selected item or only keep the selected item.

- vizDiag in the data UI shows a drill down by diagnoses or combination of diagnoses.

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/session2_data_ui_4_viz_diag_mtl_2.0.gif)](#DontLink)


### 7. Click to view the "data" tab, which show your team's individual patient information.
- Patients who have requested restricted access to their information have asterisks (****) in Columns F & G. If you are a VA provider, you can still identify patients from Column H.
- Patient information corresponds to the same categories as the team trends: diagnoses, encounters, health factor data (e.g., suicide plans, evidence-based practice templates), and measures from Mental Health Assistant.
- Providers can filter to find specific patients, or produce reports. 
- dataDiag in the data UI has an additional column after "Diagnoses of Interest," called "Primary Diagnoses", specifying which diagnosis is primary.

[![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/primary_diagnoses.png)](#DontLink)

- What **data** tab would you use to find out how many current patients on the team are engaged in a specific evidence-based psychotherapy? What column shows you the session number (EBP template) that the patient is on?
- What **viz** option would you use to see what the most common service encounters or visits are?
- Are there services that have been increasing over time? Are there services that have been decreasing over time?

## With the team trends (viz) and team patient (data) information in the data UI, your team can efficiently use team meetings to focus on the interrelated issues of care coordination and team quality improvement.


## Done and Do (15 minutes)
<!-- Do/Done Tables -->
| [<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/done.png" height = "80" width = "80">](#DontLink) **Done** | [<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/do.png" height = "90" width = "90">](#DontLink) **Do** |
| --- | --- | 
| [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) We selected the clinics that make up our team for the Team Data UI. [![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/session2_data_ui_2.gif)](#DontLink)| [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) Review the HF, Diag, Enc and SP tabs in Team Data UI to find a patient (zoom in) and find a team trend (zoom out). Log in to mtl.how/data and look at the two team folders: data_ui and team_data_table. [![](https://github.com/lzim/teampsd/blob/master/resources/gifs/mtl_2.0/session2_data_ui_4_viz_diag.gif)](#DontLink)| 

