# US Anti-Narcotics Funding of Mexico
Exploring United States foreign aid to Mexico in conjunction with cartel violence.

## Table of Contents
* [General info](#general-info)
* [Motivation](#motivation)
* [Data Sources and Tools](#technologies)
* [Challenges](#challenges)

## General Info
The war on drugs has shaped US foreign and domestic policy for decades. Particular attention has been paid to Mexico since the mid 2000s as Mexican drug cartels gained greater power and were viewed as a security threat to the United States. The US has provided foreign aid to Mexico for the purpose of fighting the war on drugs, and researchers have alleged that this has served to fracture criminal groups and increase violence. This project aims to see if there is a correlation between increased funding and drug related violence.

## Motivation
A big interest of mine is the way that seemingly abstract economic policies impact communities. There's anecdotal evidence that US funding has resulted in the intensification of drug cartel violence in Mexico. One of these is the origin of Los Zetas, the most violent drug cartel, which was started by a branch of special ops soldiers trained and equipped by the United States to combat the cartels. I wanted to see if data would show a broader pattern of violence correlated with US funding.

## Data Sources and Tools

Data on US funding to Mexico:
[foreignassistance.gov](https://foreignassistance.gov/)

foreignassistance.gov has data on US funding to foreign countries dating back to 1946. There are two classifications that made it necessary to take funding data from 2001 on: obligations and disbursements. "Obligated" funds have been appropriated or earmarked for, while "disbursed" funds are those that have been spent. There is no disbursement information before 2001.

Data on conflicts:
[Integrated Crisis Early Warning System (ICEWS) Dataverse](https://dataverse.harvard.edu/dataverse/icews)

The Integrated Crisis Early Warning System (ICEWS) is a project that aggregates data on conflicts from different news sources from around the world. The key components that allowed for me to identify drug related incidents were the "source name" and "target name" fields. Data was cleaned and consolidated to target incidents in Mexico that occurred between drug cartels and drug gangs. Each event is also categorized by its type, which allowed for me to concentrate on violent incidents.

**Python and Jupyter Notebook**  for cleaning the data
**Tableau** for visualization

## Challenges

