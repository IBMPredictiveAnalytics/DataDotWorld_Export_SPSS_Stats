# DataDotWorld_Export_SPSS_Stats
This extension allows you to export datasets to [Data.World](https://data.world/) from SPSS Statistics.

## Requirements

This extension requires the following
* IBM SPSS Statistics v25 or later
* IBM SPSS Statistics 'Essentials for R' plugin
* R v3.3


## Installation Instructions

This extension can be downloaded from the [Extension Hub](https://ibmpredictiveanalytics.github.io/)

## R packages used

This plugin will install the following R packages : 

* [Data.World](https://CRAN.R-project.org/package=data.world)
* [dwapi](https://CRAN.R-project.org/package=dwapi)
* [Properties](https://CRAN.R-project.org/package=properties)
* [stringr](https://CRAN.R-project.org/package=stringr)
* [httr](https://CRAN.R-project.org/package=httr)

## Other Requirements

This extension requires a Data.World Authentication Token. This token can be obtained from [here](https://data.world/settings/advanced)

## Steps
1. Download the extension from the Extension Hub

2. Click on File Menu -> Export -> Export to Data.World
   ![Image 1](/resources/SPSS_S_Export_Image_1.png )

3. Enter the values for the following <br/>
    a. Data.World [authentication token](https://data.world/settings/advanced). This needs to be entered only the first time the extension is used. <br/>
    b.	Title for the dataset <br/>
    c. 	Description for the dataset <br/>
    d.	Visibility: The dataset can be Public or a Private dataset <br/>
    e.	List of fields to be exported to DataDotWorld <br/>
    f.   Licensing String <br/>
   ![Image 2](/resources/SPSS_S_Export_Image_2.png)
    
4. The exported data is then available on data.world
   ![Image 3](/resources/SPSS_S_Export_Image_3.png)
   
 ## Authors
 
* Deepak Rangarao
* Amod Upadhye

## Contact Information
For any issues while using this extension, please raise an issue on GitHub or send us an <a href="mailto:h6u9j3n4w2n7k6i7@ibm-analytics.slack.com">Email</a>
