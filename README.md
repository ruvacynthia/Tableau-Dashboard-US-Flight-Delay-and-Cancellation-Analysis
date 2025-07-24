# Tableau Dashboard: US Flight Delays Analysis

This README provides an overview of the Tableau dashboard Flight Route Analysis – US Flight Delays, developed by Data Drifters.

## 📊 Dashboard Overview

This interactive Tableau dashboard visualizes key insights from US domestic flight data from 2018. It aims to assist the Federal Aviation Administration (FAA) in identifying patterns in flight delays and cancellations to improve air traffic efficiency, optimize airline operations, and enhance passenger satisfaction.

## 🎯 Objectives

The primary objectives of this analysis were to:
* Identify recurring patterns in flight delays and cancellations.
* Provide actionable insights to improve airline scheduling and operations.
*Support the enforcement of better airline accountability regarding delays and cancellations.

## ✈️ Key Insights & Findings

The dashboard highlights several critical areas:

**Airline Performance:** ExpressJet and JetBlue consistently exhibit the highest delay percentages and lower on-time performance, suggesting these carriers could be for FAA audits

**Seasonal Trends in Cancellations:** The first quarter (Q1) shows the highest number of flight cancellations, likely attributable to winter weather conditions. Summer months also indicate a rise in cancellations, possibly due to turbulence.

**High-Delay Airports:** Boston (BOS), New York (JFK), and Newark (EWR) airports are consistently identified as having higher average departure delays

**Peak Delay Months:** July and August experience longer average delays across a majority of airports.

**Most Flown Routes:** Routes such as ORD–LGA (Chicago O'Hare to LaGuardia), SFO-LAX (San Francisco to Los Angeles), and LAX-JFK (Los Angeles to New York JFK) are among the most frequently traveled and are consequently more susceptible to cumulative delays.

## 💡 Key Recommendations

Based on the analysis, the following recommendations are put forth for the FAA:
**Prioritize Delay-Prone Routes:** Investigate the root causes of delays on consistently problematic routes

**Optimize Schedules:** Implement strategies to optimize flight schedules, especially for high-traffic corridors like ORD–LGA

**Seasonal Contingency Plans:** Develop and implement seasonal contingency plans for Q1 and Q4 to mitigate weather-related disruptions

**Address Airport Inefficiencies:** Focus on improving operational efficiencies at high-delay airports, specifically BOS and JFK

**Airline Accountability:** Conduct regular audits on low-performing airlines to enforce better accountability

**Enhance Passenger Experience:** Improve real-time insights for passengers and enforce passenger rights regulations

## 📁 Data Sources
The dashboard is built upon a comprehensive dataset of **US Domestic Flights from 2018**, comprising approximately 3.8 million scheduled flights. This dataset is from Kaggle.

The key fields analyzed include:
* `Date`
* `Carrier Code`
* `Carrier`
* `Flight Number`
* `Origin`
* `Destination`
* `Scheduled Departure`
* `Departure Time`
* `Delay` (minutes)
* `Taxi Out` (minutes)
* `Wheels Off`
* `Wheels On`
* `Taxi In` (minutes)
* `Cancelled` (binary: 0 for not cancelled, 1 for cancelled)

This data is available in the `flights final dataset.csv` file..

## 🛠️ Tools Used

 **Tableau:** For data visualization and dashboard creation.

## 🧑‍💻 Presented By

This analysis was presented by:
* Christine Tadiwanashe Dzimbanhete
* Nicolette Mtisi
* Sirivennela Immadi
* Ruvarashe Cynthia Mabika
