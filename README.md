# Global Terrorism Data Exploration

## Table of Contents
1. [Introduction](#introduction)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Temporal Attributes](#a-temporal-attributes)
        - [Year](#i-year)
        - [Month](#ii-month)
        - [Day](#iii-day)
    - [Geographical Attributes](#b-geographical-attributes)
        - [Country](#i-country)
        - [Region](#ii-region)
        - [Province/State](#iii-provincestate)
        - [Latitude and Longitude](#iv-latitude-and-longitude)
    - [Incidents Characteristics](#c-incidents-characteristics)
        - [Primary Attack Type](#i-primary-attack-type)
        - [Secondary Attack Type](#ii-secondary-attack-type)
        - [Success](#iii-success)
        - [Suicide](#iv-suicide)
        - [Extended](#v-extended)
    - [Target and Victim Information](#d-target-and-victim-information)
        - [Primary Target Type](#i-primary-target-type)
        - [Target Entity](#ii-target-entity)
        - [Number of Fatalities](#iii-number-of-fatalities)
        - [Number of Injuries](#iv-number-of-injuries)
        - [Number of Hostages/Kidnapping Victims](#v-number-of-hostageskidnapping-victims)
    - [Perpetrator Information](#e-perpetrator-information)
        - [Perpetrator Group](#i-perpetrator-group)
        - [Individual](#ii-individual)
        - [Number of Perpetrators](#iii-number-of-perpetrators)
    - [Weapon Information](#f-weapon-information)
        - [Primary Weapon Type](#i-primary-weapon-type)
        - [Primary Weapon Subtype](#ii-primary-weapon-subtype)
    - [Property and Economic Impact](#g-property-and-economic-impact)
        - [Property Damage](#i-property-damage)
        - [Value of Property Damaged](#ii-value-of-property-damaged)
    - [Additional Context](#h-additional-context)
        - [Motive](#i-motive)
        - [Claimed](#ii-claimed)
        - [Ransom](#iii-ransom)
3. [Acknowledgements](#acknowledgements)
4. [Contact](#contact)
5. [EDA Endpoints](#eda-endpoints)

## Introduction
This repository contains an exploratory data analysis (EDA) of the Global Terrorism Database (GTD). The GTD is an open-source database that includes information on terrorist attacks around the world from 1970 through the present.

## Exploratory Data Analysis (EDA)

### A. Temporal Attributes

#### i. Year
Analyze trends over time to understand how terrorism has evolved.

#### ii. Month
Examine seasonal patterns in terrorist activities.

#### iii. Day
Look for specific days with the highest incidents.

### B. Geographical Attributes

#### i. Country
Identify countries with the highest number of incidents.

#### ii. Region
Understand regional patterns and hotspots.

#### iii. Province/State
Drill down to more specific locations within countries.

#### iv. Latitude and Longitude
Map the incidents for spatial analysis.

### C. Incidents Characteristics

#### i. Primary Attack Type
Determine the most common types of attack.

#### ii. Secondary Attack Type
Analyze the combination of attack types.

#### iii. Success
Evaluate the success rate of attacks.

#### iv. Suicide
Understand the prevalence of suicide attacks (1=Yes, 0=No).

#### v. Extended
Investigate incidents lasting more than 24 hours (1=Yes, 0=No).

### D. Target and Victim Information

#### i. Primary Target Type
Identify common targets of attacks.

#### ii. Target Entity
Details of specific target entities.

#### iii. Number of Fatalities
Analyze the human cost of terrorism.

#### iv. Number of Injuries
Assess the impact on victims.

#### v. Number of Hostages/Kidnapping Victims
Examine incidents involving hostages.

### E. Perpetrator Information

#### i. Perpetrator Group
Identify groups responsible for the most incidents.

#### ii. Individual
Look into incidents carried out by individuals (1=Yes, 0=No).

#### iii. Number of Perpetrators
Analyze the group size involved in incidents.

### F. Weapon Information

#### i. Primary Weapon Type
Determine the most commonly used weapons.

#### ii. Primary Weapon Subtype
Further detail on weaponry.

### G. Property and Economic Impact

#### i. Property Damage
Incidents involving property damage.

#### ii. Value of Property Damaged
Financial cost of incidents.

### H. Additional Context

#### i. Motive
Explore the motives behind the attacks.

#### ii. Claimed
Understand if incidents were claimed by groups.

#### iii. Ransom
Investigate incidents involving ransom demands.

## Acknowledgements
We would like to acknowledge the Global Terrorism Database (GTD) team at the University of Maryland for providing this comprehensive and valuable dataset.

## Contact
For any questions or feedback, please contact Jacob Jaroya at jaroyajo@gmail.com.

## EDA Endpoints

1. [Yearly Analysis](#)
2. [Geographical Distribution](#)
3. [Attack Types](#)
4. [Impact Analysis](#)
5. [Perpetrator Information](#)

---

This README provides an outline of the exploratory data analysis (EDA) conducted on the Global Terrorism Database (GTD). Each section of the EDA aims to uncover patterns and insights into the nature and impact of terrorism worldwide. The endpoints listed will lead to detailed analyses and visualizations for each attribute category.

## Author: 
Jacob Jaroya