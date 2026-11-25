# HR Workforce Analysis (EDF Group)

Excel dashboard on EDF Group's published HR indicators: workforce, hires, departures by reason, turnover, managers share and age mix, 2012 to 2024.

## Source and licence
Data: EDF SA, "Indicateurs sociaux du groupe EDF", https://opendata.edf.fr/explore/dataset/indicateurs-sociaux/information/ , Licence Ouverte / Open Licence 2.0, data last updated 5 December 2025. This is my own analysis, not an EDF product, and EDF does not endorse it.

## Contents
`EDF_HR_Dashboard.xlsx`: Dashboard (charts and key figures), Analysis (indicator tables), Clean_Data (selected indicators, values as published), Validation (my checks, including source mismatches), Notes (source, scope and limits). `dashboard_preview.png` is a rendered image of the Dashboard sheet.

## Code
The analysis was prepared with Python (selecting and organising the indicators) and SQL (hiring, resignation and age questions) before the Excel build. This repository currently holds the workbook and preview only; the scripts are not included here.

## Limits
- The workforce total jumps 9.0% from 2017 to 2018 where the source label changes; the cause is not documented, so compare across that point with caution.
- A few published figures do not reconcile (2022 managers plus non-management, and exits/workforce for 2021 and 2024). Published values are kept, not corrected.
- Departures shown are resignations, retirements and dismissals/redundancies only, not all leavers.
