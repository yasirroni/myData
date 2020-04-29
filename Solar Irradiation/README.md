# Washington DC Solar Radiation from NREL

## Data
Data: WASHINGTON DC DULLES INT'L AR [STERLING - ISIS], VA.

Source: https://rredc.nrel.gov/solar/old_data/nsrdb/1991-2010/hourly/siteonthefly.cgi?id=724030

Reason: The best meteorological site (lowest uncertainty) that has Solar measurements and also the nearest to White House.

Column: P, 16. METSTAT Glo (Wh/m^2)

Unit: Wh/m^2

Row (hours in one year): 8760

Total Data: 166560, from 19 learn File

Days: 6940, from 19 learn File

Number of File: 19 for learn, 1 for test

User Manual: https://www.nrel.gov/docs/fy12osti/54824.pdf

## Setting for K-Means (creating learn data set)
Seed: 0

Number of Cluster: 1 to 10

Algorithm: full

Solver: sklearn

File Source: 19 learn file

## Note
Explanation of METSTAT Glo: Total amount of direct and diffuse solar radiation received on a horizontal surface during the 60-minute period ending at the timestamp