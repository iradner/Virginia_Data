#DBHDS Data Analysis Readme


This repo contains the files + analysis of data for the state of Virginia's Department of Behavioral Health and Developmental Services (DBHDS). 

###Data
The data was pulled from the [Virginia Social Indicator Dashboard](https://vasisdashboard.omni.org/rdPage.aspx?rdReport=Home). 

The documentation on the data from this source is as follows:

"Behavioral health services data are provided by the Virginia Department of Behavioral Health & Developmental Services, from the Community Consumer Submission 3 (CCS3) dataset. The CCS3 is used by DBHDS and community service boards (CSBs) to collect information on the number and characteristics of individuals receiving direct and contracted mental health, developmental and substance abuse services from CSBs. Only data from mental health and substance abuse services are included on the dashboard. 

Data reflect information collected at admission to care and may be duplicated across individuals receiving multiple episodes of care over the time period captured on the dashboard. Individuals may also be duplicated across Program Type, reflecting provision of substance abuse and/or mental health treatment services. Geographic data is presented at the CSB level and reflects place of service provision, not residence of the individual seeking services. Per DBHDS requirements, data are suppressed if counts equal less than ten cases. For more information, please visit: http://www.dbhds.virginia.gov/professionals-and-service-providers/office-of-support-services"

* Link to data file: [DBHDS Data File](https://github.com/iradner/hw05/blob/master/DBHDS%20-%20export.xlsx)

###Packages 
In addition to standard r packages, the analysis uses [kableExtra](https://github.com/haozhu233/kableExtra), [readxl](https://readxl.tidyverse.org/), and [ggcorrplot](http://www.sthda.com/english/wiki/ggcorrplot-visualization-of-a-correlation-matrix-using-ggplot2).

* *kableExtra* allows for the creation of formatted tables in the markdown file. 

* *readxl* is used to import the specific sheets from the original excel data file.

* *ggcorrplot* is used to visually display correlation heatmaps. 

###Analysis

* Link to markdown file with R code displayed: [DBHDS data analysis (with code)](https://github.com/iradner/hw05/blob/master/Data_Analysis.md)

* Link to markdown file _without_ R code displayed: [DBHDS data analysis (without code)](https://github.com/iradner/hw05/blob/master/Data_Analysis_false.md)



