# dormancy_ArnoldArb


Data and code for analysis of cold hardiness effects on budbreak for 15 different species for the manuscript "Woody species do not differ in dormancy progression: Differences in time to budbreak due to forcing and cold hardiness"

.csv files with number 2 in file names refer to 2020-2021 season data. No number indicates 2019-2020 season.

## File descriptions

### Dormancy_ArnoldArb_2y.Rmd

R Markdown file used for data analysis. First code chunk (line 12-1228) are data analysis. Following code chunks generate figures from the manuscript.


### ChillCurve.csv and ChillCurve2.csv

Species: Species names for plants used. "Forsythia" is Forsythia x 'Meadowlark'. "Kalmia" is Kalmia latifolia. "Rhododendron" is Rhododendron calendulaceum

Following column IDs: YYMMDDCC, where YY is year; MM is month; DD is day; and CC is collection. Some columns include a timepoint label (e.g., T00), which can be ignored.

Measurements are cold hardiness shown as positive degrees C.

### Budbreak.csv and Budbreak2.csv

Data for budbreak (date of budbreak) in controlled environment at 22C for 10 cuttings at each collection for each species.

Species: Species names for plants used. "Forsythia" is Forsythia x 'Meadowlark'. "Kalmia" is Kalmia latifolia. "Rhododendron" is Rhododendron calendulaceum

Following column IDs: Collection from which dates of budbreak for single cuttings are shown.

### fieldbb.csv

Data for budbreak in the field for the species studied.

Species: Species names for plants used. "Forsythia" is Forsythia x 'Meadowlark'. "Kalmia" is Kalmia latifolia. "Rhododendron" is Rhododendron calendulaceum

Following column IDs: date of observation

Data: estimated percent budbreak for the entire plant.


### Temp.csv and Temp2.csv

Data for cold hardiness loss at different temperatures

Species: Species names for plants used. "Forsythia" is Forsythia x 'Meadowlark'. "Kalmia" is Kalmia latifolia. "Rhododendron" is Rhododendron calendulaceum

Temperature: Temperature in C cuttings were subjected to

Following column IDs: date of measurement

Measurements are cold hardiness shown as positive degrees C.


### weather2019_2020.csv and weather2020_2021.csv

Weather data from Weld Hill weather station

Date: "%m/%d/%y %H:%M" format

Temperature: temperature recorded in Farenheit
