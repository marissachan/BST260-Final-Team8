# Missing Migrants: Uncovering Trends in Migration Routes
Final project from team 8: Missing Migrants

Missing Migrants Project aims to document “number of people who died or disappeared in the process of migration towards an international destination.” With a count surpassing 35,000 lives lost during migration since 2014, International Organization for Migration (IOM) calls on all the world’s governments to address what it describes as “an epidemic of crime and abuse.” The motivation behind this project began with the October 2013 tragedies, when at least 368 individuals died in two shipwrecks near the Italian island of Lampedusa. 

IOM’s Missing Migrants Project tracks deaths of migrants, including refugees and asylum-seekers, who have gone missing along mixed migration routes worldwide. Since then, Missing Migrants Project has developed into an important hub and advocacy source of information that media, researchers, and the general public access for the latest information. The project is a joint initiative of IOM’s Global Migration Data Analysis Centre (GMDAC) and Media and Communications Division (MCD). 

Data: https://missingmigrants.iom.int/downloads

Datasets:
- MMdf.csv : Combined missing migrants dataset from 2014-2021
- 2014.csv : 2014 missing migrants data
- 2015.csv: 2015 missing migrants data
- 2016.csv: 2016 missing migrants data
- 2017.csv: 2017 missing migrants data
- 2018.csv: 2018 missing migrants data
- 2019.csv: 2019 missing migrants data
- 2020.csv: 2020 missing migrants data
- 2021.csv: 2021 missing migrants data

## Data Dictionary for MMdf (modified based on the Missing Migrant Project's Data Dictionary)

Variable [name in dataset] and description 
1. `[X]`: Auto generated number for each entry in the data set (1-9705).
2. `Web [id]/ 3. Event ID [event_id]`: An automatically generated number used to identify each unique entry in the dataset.
4. `Region of incident [region]`: The region in which an incident took place. For more about regional classifications used in the dataset, click here.
5. `Event date [event_date]`: Estimated date of death. In cases where the exact date of death is not known, this variable indicates the date in which the body or bodies were found. In cases where data are drawn from surviving migrants, witnesses or other interviews, this variable is entered as the date of the death as reported by the interviewee.  At a minimum, the month and the year of death is recorded. In some cases, official statistics are not disaggregated by the incident, meaning that data is reported as a total number of deaths occurring during a certain time period. In such cases the entry is marked as a “cumulative total,” and the latest date of the range is recorded, with the full dates recorded in the comments.
6. `Reported year [year]`: The year in which the incident occurred.
7. `Reported month [month]`: The month in which the incident occurred.
8. `Count of dead [count_dead]`: The total number of people confirmed dead in one incident, i.e. the number of bodies recovered.  If migrants are missing and presumed dead, such as in cases of shipwrecks, leave blank.
9. `Minimum missing [min_missing]`: The total number of those who are missing and are thus assumed to be dead.  This variable is generally recorded in incidents involving shipwrecks.  The number of missing is calculated by subtracting the number of bodies recovered from a shipwreck and the number of survivors from the total number of migrants reported to have been on the boat.  This number may be reported by surviving migrants or witnesses.  If no missing persons are reported, it is left blank.
10. `Total dead and missing [tot_missing]`: The sum of the ‘number dead’ and ‘number missing’ variables.
11. `Count of survivors [count_survivors]`: The number of migrants that survived the incident, if known. 
12. `Count of females [count_female]`: Indicates the number of females found dead or missing. If unknown, it is left blank. This gender identification is based on a third-party interpretation of the victim's gender from information available in official documents, autopsy reports, witness testimonies, and/or media reports.
13. `Count of males [count_male]`: Indicates the number of males found dead or missing. If unknown, it is left blank. This gender identification is based on a third-party interpretation of the victim's gender from information available in official documents, autopsy reports, witness testimonies, and/or media reports.
14. `Count of children [count_child]`: Indicates the number of individuals under the age of 18 found dead or missing. If unknown, it is left blank.
15. `Cause of death [cause_death]`: The determination of conditions resulting in the migrant's death i.e. the circumstances of the event that produced the fatal injury. If unknown, the reason why is included where possible.  For example, “Unknown – skeletal remains only”, is used in cases in which only the skeleton of the decedent was found.
16. `Location description [loc_death]`: Place where the death(s) occurred or where the body or bodies were found. Nearby towns or cities or borders are included where possible. When incidents are reported in an unspecified location, this will be noted.
17. `Information source [info_source]`: Name of source of information for each incident. Multiple sources may be listed.
18. `Coordinates [coordinates]`: Place where the death(s) occurred or where the body or bodies were found. In many regions, most notably the Mediterranean, geographic coordinates are estimated as precise locations are not often known. The location description should always be checked against the location coordinates.
19. `Migration route [migration_route]`:Name of the migrant route on which incident occurred, if known. If unknown, it is left blank.
20. `Link [url]`: Links to original reports of migrant deaths / disappearances if available. Multiple links may be listed.
21. `UNSD geographical grouping [unsd_geo_group]`: Geographical region in which the incident took place, as designated by the United Nations Statistics Division (UNSD) geoscheme. 
22. `Source quality [source_qual]`: Incidents are ranked on a scale from 1-5 based on the source(s) of information available. Incidents ranked as level 1 are based on information from only one media source. Incidents ranked as level 2 are based on information from uncorroborated eyewitness accounts or data from survey respondents. Incidents ranked as level 3 are based on information from multiple media reports, while level 4 incidents are based on information from at least one NGO, IGO, or another humanitarian actor with direct knowledge of the incident. Incidents ranked at level 5 are based on information from official sources such as coroners, medical examiners, or government officials OR from multiple humanitarian actors.


