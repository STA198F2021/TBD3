# data

Place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## data origin
[Replication Data for: Associations of Urbanicity and Sociodemographic Characteristics with Protective Health Behaviors and Reasons for Leaving the Home during COVID-19](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/7FA07D)

## codebook
1. participant_id: Participant ID
2. age: age in years
3. usres: Do you currently live in the United States?
4. state: What state do you live in? (numbers associated with each state)
```
   1 - Alabama
   2 - Alaska  
   3 - Arizona  
   4 - Arkansas  
   5 - California  
   6 - Colorado
   7 - Connecticut
   8 - District of Columbia (DC)
   9 - Delaware
   10 - Florida
   11 - Georgia
   12 - Hawaii
   13 - Idaho
   14 - Illinois
   15 - Inidana
   16 - Iowa
   17 - Kansas
   18 - Kentucky
   19 - Louisiana
   20 - Maine
   21 - Maryland
   22 - Massachusetts
   23 - Michigan
   24 - Minnesota
   25 - Mississippi
   26 - Missouri
   27 - Montana
   28 - Nebraska
   29 - Nevada
   30 - New Hampshire
   31 - New Jersey
   32 - New Mexico
   33 - New York
   34 - North Carolina
   35 - North Dakota
   36 - Ohio
   37 - Oklahoma
   38 - Oregon
   39 - Pennsylvania
   40 - Rhode Island
   41 - South Carolina
   42 - South Dakota
   43 - Tennessee
   44 - Texas
   45 - Utah
   46 - Vermont
   47 - Virginia
   48 - Washington
   49 - West Virginia
   50 - Wisonsin
   51 - Wyoming
```
5. race - What is your race?
```
  0 - American Indian/Alaska Native
  1 - Asian
  2 - Native Hawaiian or Other Pacific Islander
  3 - Black or African American
  4 - White
  5 - More than one race
  6 - Unknown/not reported
```
6. sex - What was your sex at birth?
```
  1 - Male
  2 - Female
```
7. localsip - Are you currently required by state or local (county, city) laws to "stay at home"?
```
  1 - Yes
  2 - No
  7 - Don't know/Not sure
```
8. localsip2 (if `localsip == 2`) - Even though there is no formal order to "stay at home," are you staying at home as much as possible?
```
  1 - Yes
  2 - No
```
9. localsip3 (if `localsip == 7`) - Even though there is no formal order to "stay at home," are you staying at home as much as possible?
```
  1 - Yes
  2 - No
```
10. leavehomeact - If you leave your home for any reason, what do you do to protect yourself when out in public? (check all that apply)
```
  1 - yes (box was checked)
  0 - no (box was not checked)
  
  leavehomeact_1 - social distancing (staying at least 6 feet away from others)
  leavehomeact_2 - wearing a protective mask
  leavehomeact_3 - wearing gloves
  leavehomeact_4 - using hand sanitizer
  leavehomeact_5 - using disinfectant wipes
  leavehomeact_6 - washing hands frequently
  leavehomeact_7 - removing clothes before re-entering home
  leavehomeact_8 - other
```
11. leavehomereason - For what reasons have you left your home during the "stay in place" order? (check all that apply)
```
  1 - yes (box was checked)
  0 - no (box was not checked)
  
  leavehomereason_1 - work 
  leavehomereason_2 - provide care for someone else
  leavehomereason_3 - grocery shopping
  leavehomereason_4 - other essential shopping
  leavehomereason_5 - exercise
  leavehomereason_6 - walking dog
  leavehomereason_7 - other
```
12. localsiphours - On average, how many hours per day (out of 24-hours) have you remained at home during COVID outbreak? (integer, min: 0, max: 24)
13. covidsick - Do you think you have been sick from COVID?
```
  1 - Yes
  2 - No
  3 - Maybe (had symptoms)
```
14. hhcovidsick - Do you think anyone in your household been sick from COVID?
```
  1 - Yes
  2 - No
  3 - Maybe (had symptoms)
```
15. ffcovidsick - Do you think any of your close friends or family members outside of your household been sick from COVID?
```
  1 - Yes
  2 - No
  3 - Maybe (had symptoms)
```
16. Classification
```
  Urban
  Suburban
  Rural
```
17. covidtest - Have you been tested for COVID?
```
  1 - Yes
  2 - No
```
18. educ - What is the highest grade or year of school you completed?
```
  1 - Never attended school or only kindergarten
  2 - grades 1 through 8 (elementary)
  3 - grades 9 through 11 (some high shcool)
  4 - grade 12 or GED (high school graduate)
  5 - some college or technical school
  6 - college 4 years or more (college graduate)
  7 - don't know/not sure
```
19. hhincome - annual income from all sources
```
  1 - less than $9,999
  2 - $10,000 to $19,999
  3 - $20,000 to $29,999
  4 - $30,000 to $39,999
  5 - $40,000 to $49,999
  6 - $50,000 to $59,999
  7 - $60,000 to $69,999
  8 - $70,000 to $79,999
  9 - $80,000 to $89,999
  10 - $90,000 to $99,999
  11 - $100,000 to $150,000
  12 - over $150,000
```
## data

Rows: 2,441

Columns: 66
```
$ Key_ID                <int> 916, 1377, 1372, 40, 1005, 1632, 629, 1764, 236, 1406, 32, 1342, 304, 531, 1508, 1237, 507, 776, 1064, 1216, 1246, 604, 1069, 1760, 963, 1738, 1233, 1309, 1302, 1655, 1292, 1266, 605, 705, …
$ Participant_ID        <int> 1, 2, 3, 4, 5, 6, 7, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 22, 25, 26, 27, 28, 29, 30, 32, 34, 37, 38, 39, 42, 43, 44, 45, 47, 48, 49, 50, 51, 52, 53, 54, 57, 59, 60, 62, 63, 64, 6…
$ zip                   <int> 75233, 75001, 75002, 97702, 75204, 27517, 77025, 6515, 78754, 63130, 98038, 75019, 78671, 77095, 49525, 75019, 77354, 76131, 75080, 75019, 75019, 77035, 75078, 7016, 75218, 11222, 75019, 75…
$ Classification        <fct> Urban, Urban, Suburban, Rural, Urban, Rural, Urban, Urban, Suburban, Urban, Rural, Suburban, Rural, Urban, Suburban, Suburban, Rural, Suburban, Urban, Suburban, Suburban, Urban, Rural, Urba…
$ age                   <int> 27, 26, 27, 23, 24, 40, 36, 35, 28, 36, 31, 31, 55, 24, 39, 31, 35, 34, 42, 62, 41, 56, 42, 38, 40, 35, 34, 47, 44, 36, 40, 32, 63, 32, 33, 39, 31, 45, 35, 56, 41, 38, 33, 45, 67, 34, 48, 3…
$ usres                 <int> 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, …
$ state                 <int> 44, 44, 44, 38, 44, 34, 44, 7, 44, 26, 48, 44, 44, 44, 23, 44, 44, 44, 44, 44, 44, 44, 44, 31, 44, 33, 44, 44, 44, 47, 44, 44, 44, 44, 44, 44, 5, 44, 44, 44, 44, 44, 44, 44, 44, 34, 44, 21,…
$ ethnicity             <int> 2, 1, 2, 2, 2, 2, 1, 2, 2, 1, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, NA, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 2, 2, 2, 2, NA…
$ race                  <int> 5, 4, 4, 5, 1, 4, 5, 4, 4, 4, 4, 4, 4, 1, 6, 4, 4, 4, 4, 4, 4, 4, 4, 1, 4, 4, 4, 4, 1, 4, 4, 4, 4, 4, 4, 4, 4, 1, 4, 4, 4, 4, 4, 4, 4, 4, 1, 3, 4, 4, 4, 4, 1, 4, 4, 4, 4, 4, 4, 4, 4, 4, 4, …
$ sex                   <int> 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 1, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 2, 1, 1, 2, 2, 1, 2, 2, 1, 2, 2, 2, 1, 2, 1, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, …
$ hhchildren            <int> 0, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1, 1, 0, 3, 0, 2, 0, 0, 0, 0, 2, 1, 1, 2, 3, 0, 2, 2, 3, NA, 2, 3, 0, 3, 2, 2, 2, 0, 2, 1, 1, 2, 0, 3, 3, 0, 0, 2, 3, 0, 2, 0, 0, 0, 2, 2,…
$ covidtest             <int> 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, …
$ covidtestresult       <int> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, N…
$ covidsick             <int> 2, 2, 2, 2, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 3, 2, 2, 3, 3, 2, 2, 3, 3, 3, 2, 2, 2, …
$ covidsickoutcome      <int> NA, NA, NA, NA, NA, NA, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA, NA, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA…
$ hhcovidsick           <int> 2, 2, 2, 2, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 3, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 3, 2, 2, 2, 2, 2, 2, 3, 2, NA, 2, 2, 2,…
$ hhcovidsickoutcome    <int> NA, NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 2, NA, NA, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA…
$ ffcovidsick           <int> 2, 3, 1, 2, 3, 1, 1, 4, 3, 4, 2, 2, 4, 1, 4, 2, 2, 2, 4, 1, 2, 2, 4, 1, 1, 2, 3, 3, 2, 2, 1, 2, 2, 4, 2, 2, 2, 4, 2, 2, 2, 2, 2, 2, 2, 2, 2, 4, 2, 4, 3, 2, 4, 3, 4, 3, 1, 4, 1, 3, 2, 4, 2, …
$ hhcovidsickoutcome_2  <int> NA, 1, 2, NA, 1, 2, 1, NA, 1, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, 1, NA, NA, NA, 2, 2, NA, 4, 2, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1,…
$ dis_any               <int> 2, 2, 2, 2, 2, 1, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 1, 2, 2, 2, …
$ dis_mobility          <int> NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, …
$ dis_alone             <int> NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, …
$ comorbid              <int> 2, 1, 2, 2, 2, 1, 1, 1, 1, 2, 2, 2, 2, 1, 2, 2, 2, 2, 1, 2, 2, 2, 1, 1, 2, 1, 1, 1, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 1, 2, 2, 1, 2, 1, 2, 1, 2, 2, 2, 1, 2, 1, 2, 1, 1, 2, 1, 2, 1, …
$ comborbid_heartattack <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_chd         <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_stroke      <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_asthma      <int> NA, 1, NA, NA, NA, 1, 0, 0, 0, NA, NA, NA, NA, 1, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 1, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 1, NA, NA, 0, NA, 1, NA, 1, NA, N…
$ comborbid_skincancer  <int> NA, 0, NA, NA, NA, 0, 0, 1, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_othcancer   <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_copd        <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_arthritis   <int> NA, 0, NA, NA, NA, 1, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 1, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 1, NA, 0, NA, 1, NA, N…
$ comborbid_depression  <int> NA, 1, NA, NA, NA, 1, 1, 1, 1, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 1, 0, NA, 0, 1, 1, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_kidneydis   <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_diabetes    <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_obesity     <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 1, NA, NA, NA, 0, 1, NA, 0, 1, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 1, NA, 0, NA, 1, NA, N…
$ comborbid_parkinsons  <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ comborbid_alzheimers  <int> NA, 0, NA, NA, NA, 0, 0, 0, 0, NA, NA, NA, NA, 0, NA, NA, NA, NA, 0, NA, NA, NA, 0, 0, NA, 0, 0, 0, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, 0, NA, NA, 0, NA, 0, NA, 0, NA, N…
$ educ                  <int> 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 4, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 5, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 5, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, 6, …
$ hhincome              <int> 12, 11, 11, 5, 3, 7, 3, 6, 12, 12, 12, 12, 12, 12, 8, 12, 11, 11, 12, 12, 12, 12, 11, 11, 9, 12, 4, 11, 12, 11, 12, 11, 12, 9, 8, 12, 12, 12, 5, 12, 12, 11, 11, 12, 6, 11, 11, 12, 12, 11, 1…
$ employ1               <int> 1, 1, 1, 6, 1, 1, 1, 1, 1, 1, 1, 1, 1, 6, 2, 1, 1, 1, 1, 1, 5, 1, 2, 1, 1, 1, 1, 4, 1, 1, 1, 1, 2, 1, 5, 1, 1, 1, 5, 1, 5, 1, 5, 5, 7, 5, 2, 1, 1, 7, 1, 1, 4, 1, 2, 1, 1, 5, 5, 1, 1, 1, 1, …
$ localsip              <int> 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, …
$ localsipweeks         <fct> "5", "3", "4", "I don't know", "2", "5", "2", "i don't know", "2", "4", "4", "4.5", "4", "3", "5", "5", "3", "2+ weeks", "4", "3 weeks", "4", "3", "5", "4", "4weeks", "4 so far", "6", "4", …
$ localsip2             <int> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, N…
$ localsip3             <int> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, N…
$ leavehomeact___1      <int> 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, …
$ leavehomeact___2      <int> 0, 1, 1, 0, 1, 1, 1, 0, 1, 1, 0, 1, 1, 0, 0, 1, 0, 0, 1, 1, 1, 1, 0, 1, 0, 1, 1, 1, 1, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 0, 1, 0, 1, 0, 1, 1, 1, 1, 0, 1, 1, 1, 1, 0, 1, 0, 0, 1, 1, 0, 1, 1, 1, …
$ leavehomeact___3      <int> 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, …
$ leavehomeact___4      <int> 1, 1, 1, 0, 1, 1, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, …
$ leavehomeact___5      <int> 1, 1, 0, 0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 1, 1, 1, 0, 1, 1, 1, 1, 1, 0, 0, 0, 0, 1, 1, 0, 0, 0, 0, 1, 1, 1, 0, 0, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 0, 0, 0, 1, 0, 0, 0, 1, 1, 1, 0, …
$ leavehomeact___6      <int> 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 0, …
$ leavehomeact___7      <int> 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 1, 0, …
$ leavehomeactother     <fct> "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "", "…
$ leavehomereason___1   <int> 1, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 1, 1, 1, 0, 0, 1, 0, 0, 0, 1, 1, 0, 1, 1, 1, 0, 0, 1, 1, 0, 1, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, …
$ leavehomereason___2   <int> 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, …
$ leavehomereason___3   <int> 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 0, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 0, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 0, 1, 0, 1, 1, 1, …
$ leavehomereason___4   <int> 0, 1, 1, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 1, 1, 1, 0, 0, 0, 0, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 1, 0, 0, 1, 1, 1, 0, 1, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 0, 1, …
$ leavehomereason___5   <int> 0, 0, 0, 1, 0, 1, 1, 0, 1, 0, 0, 1, 0, 0, 0, 1, 0, 1, 0, 0, 1, 1, 1, 1, 1, 0, 1, 0, 1, 1, 1, 1, 1, 0, 1, 1, 1, 1, 0, 0, 1, 1, 1, 1, 1, 1, 1, 0, 1, 1, 1, 0, 0, 1, 1, 0, 0, 1, 1, 0, 0, 1, 1, …
$ leavehomereason___6   <int> 0, 1, 0, 0, 0, 0, 0, 1, 0, 1, 0, 0, 1, 0, 0, 0, 1, 0, 1, 1, 0, 1, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1, 1, 1, 0, 0, 1, 1, 0, 1, 1, 0, 1, 1, 1, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0, 1, 1, 0, …
$ leavehomereason___7   <int> 0, 0, 0, 0, 0, 1, 0, 0, 0, 1, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, …
$ leavehomereasonother  <fct> "", "", "", "", "", "Going for a drive", "", "", "", "Doctor's appointment and pharmacy visits", "Get mail", "", "", "", "", "Doctor's Appointments", "", "", "", "", "vaccine shots for 4 mo…
$ essntlsrvcs           <fct> "1", NA, NA, "1", NA, NA, NA, NA, "1", NA, NA, NA, "7", "1", "1", NA, NA, "1", NA, NA, NA, "1", "2", NA, "1", "2", "1", NA, NA, "7", "1", NA, "1", "1", NA, NA, "1", NA, NA, NA, NA, NA, NA, …
$ essntlsrvcstype       <int> 1, NA, NA, 1, NA, NA, NA, NA, 1, NA, NA, NA, NA, 1, 1, NA, NA, 1, NA, NA, NA, 1, NA, NA, 2, NA, 1, NA, NA, NA, 9, NA, 18, 19, NA, NA, 2, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, …
$ localsiphours         <int> 14, 23, 24, 14, 24, 24, 23, 24, 24, 22, 24, 20, 22, 14, 23, 23, 23, 23, 23, 23, 23, 24, 24, 22, 11, 22, 17, 23, 23, 22, 21, 21, 15, 23, 23, 23, 12, 22, 24, 23, 22, 23, 23, 23, 23, 24, 22, 2…
$ phq_sum               <int> 4, 18, 12, 2, 6, 16, 12, 18, 16, 8, 0, 6, 23, 0, 0, 11, 3, 1, 11, 3, 6, 1, 20, 6, 7, 2, 13, 11, NA, 0, 5, 1, 0, 5, 12, 4, 8, 4, 7, 0, 9, 9, 3, 7, 4, 17, 4, 1, 0, 2, 16, 0, 0, 7, 5, 4, 12, 6…
$ X                     <int> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, N…
$ X.1                   <int> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, N…
```
