# Data Dict


## Raw Data

#### 20210414_covid_de.csv

"COVID-19 cases and deaths which will be updated daily. The original data are being collected by Germany's Robert Koch Institute and can be download through the National Platform for Geographic Data (the latter site also hosts an interactive dashboard). I reshaped and translated the data (using R tidyverse tools) to make it better accessible. The earliest recorded cases are from 2020-01-24.""

Source: https://www.kaggle.com/headsortails/covid19-tracking-germany?select=covid_de.csv, 2021.04.17

- **state:** German Federal State
- county: German Stadt/Landkreis
- age_group: Age Group
- gender: Gender
- **date:** Date of reporting
- **cases:** Daily number of COVID-19 cases
- **deaths:** Daily number of COVID-19 deaths
- **recovered:** Daily number of recovered cases

#### 20210414_covid_de_vaccines.csv

"COVID-19 vaccination progress; updated daily. Derived from Impfdashboard.de. The earliest data are from 2020-12-27."

Source: https://www.kaggle.com/headsortails/covid19-tracking-germany?select=covid_de_vaccines.csv, 2021.04.17

- **date:** Date
- **doses:** Daily doses administered.
- **doses_first:** Daily 1st doses.
- **doses_second:** Daily 2nd doses.
- pfizer_cumul: Cumulative doses of Pfizer-Biontech vaccine.
- moderna_cumul: Cumulative doses of Moderna vaccine.
- astrazeneca_cumul: Cumulative doses of AstraZeneca vaccine.
- **persons_first_cumul:** Cumulative number of people having received their 1st vaccination.
- **persons_full_cumul:** Cumulative number of fully vaccinated people.

#### 20181231_demographics_de.csv

"General Demographic Data about Germany on the federal state level. Those have been downloaded from Germany's Federal Office for Statistics (Statistisches Bundesamt) through their Open Data platform GENESIS. The data reflect the (most recent available) estimates on 2018-12-31."

Source: https://www.kaggle.com/headsortails/covid19-tracking-germany?select=demographics_de.csv, 2021.04.17

- **state:** German Federal State
- gender: Gender
- age_group: Age Group
- **population:** Population

#### 20210414_taegliches_mobilitaetsgeschehen.csv

Change in mobility compared to the respective month in 2019 aggregated for the individual federal states as well as for Germany as a whole.

Source https://www.destatis.de/DE/Service/EXDAT/Datensaetze/mobilitaetsindikatoren-mobilfunkdaten.html, 2021.04.17

- **Tag:** Date
- **BW:** Change in mobility compared to the respective month in 2019 in Baden-Wuerttemberg
- **BY:** Change in mobility compared to the respective month in 2019 in Bayern
- **BE:** Change in mobility compared to the respective month in 2019 in Berlin
- **BB:** Change in mobility compared to the respective month in 2019 in Brandenburg
- **HB:** Change in mobility compared to the respective month in 2019 in Bremen
- **HH:** Change in mobility compared to the respective month in 2019 in Hamburg
- **HE:** Change in mobility compared to the respective month in 2019 in Hessen
- **MV:** Change in mobility compared to the respective month in 2019 in Mecklenburg-Vorpommern
- **NI:** Change in mobility compared to the respective month in 2019 in Niedersachsen
- **NW:** Change in mobility compared to the respective month in 2019 in Nordrhein-Westfalen
- **RP:** Change in mobility compared to the respective month in 2019 in Rheinland-Pfalz
- **SL:** Change in mobility compared to the respective month in 2019 in Saarland
- **SN:** Change in mobility compared to the respective month in 2019 in Sachsen
- **ST:** Change in mobility compared to the respective month in 2019 in Sachsen-Anhalt
- **SH:** Change in mobility compared to the respective month in 2019 in Schleswig-Holstein
- **TH:** Change in mobility compared to the respective month in 2019 in Thueringen
- **DE:** Change in mobility compared to the respective month in 2019 in Germany

#### https://www.kaggle.com/headsortails/covid19-tracking-germany?select=demographics_de.csv

"The CSV file /data/OxCGRT_latest.csv reports country/territory- and state-level data presented in "country/territory-day" format (or "state-day" as the case may be), with a list of all indicators for each country/territory as a single row each day. This CSV is updated every hour from the main database, and the badge above shows whether this data link is functioning correctly."

Source: https://github.com/OxCGRT/covid-policy-tracker, 2021.04.17


- **CountryName**
- CountryCode
- RegionName
- RegionCode
- Jurisdiction
- Date
- C1_School closing
- C1_Flag
- C2_Workplace closing
- C2_Flag
- C3_Cancel public events
- C3_Flag
- C4_Restrictions on gatherings
- C4_Flag
- C5_Close public transport
- C5_Flag
- C6_Stay at home requirements
- C6_Flag
- C7_Restrictions on internal movement
- C7_Flag
- C8_International travel controls
- E1_Income support
- E1_Flag
- E2_Debt/contract relief
- E3_Fiscal measures
- E4_International support
- H1_Public information campaigns
- H1_Flag
- H2_Testing policy
- H3_Contact tracing
- H4_Emergency investment in healthcare
- H5_Investment in vaccines
- H6_Facial Coverings
- H6_Flag
- H7_Vaccination policy
- H7_Flag
- H8_Protection of elderly people
- H8_Flag
- M1_Wildcard
- ConfirmedCases
- ConfirmedDeaths
- StringencyIndex
- **StringencyIndexForDisplay**
- StringencyLegacyIndex
- StringencyLegacyIndexForDisplay
- GovernmentResponseIndex
- GovernmentResponseIndexForDisplay
- ContainmentHealthIndex
- ContainmentHealthIndexForDisplay
- EconomicSupportIndex
- EconomicSupportIndexForDisplay