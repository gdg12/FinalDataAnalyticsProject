# FinalDataAnalyticsProject
Final Project for ENV 872 

Populate your README with the necessary information for the project. Use the Environmental Data Analytics repository README and the associated README files for datasets as a guide.

##Summary
This dataset was prepared for the Environmental Data Analytics (ENV 872L) Final Project at Duke University for Spring 2019.
The dataset contains data from the Statewide Water Quality Sampling Dataset from 373 coastal monitoring sites in Hawaii from 1999-2019.

#Database Information
Water quality Data was sampled by the State of Hawaii Department of Health Clean Water Branch (specifically, their Beach Monitoring Program). More information can be found here: 
http://health.hawaii.gov/cwb/


Data were collected from the Clean Water Branch's Water Quality Data website. More information can be found here: http://cwb.doh.hawaii.gov/CleanWaterBranch/WaterQualityData/default.aspx
From this page, Spreadsheet Download Request was selected, and thus the following selections were made: 


Island: Oahu 
Date from: 01/01/1999
Date Through: 04/12/2019


A list of all sample sites in Hawaii (for all the islands) are listed here:
http://health.hawaii.gov/cwb/clean-water-branch-home-page/sample-sites/


The file was converted into a csv file and saved as `OahuData.csv'. 

Data were accessed 2019-04-01.

# Data Content Information
From the 2018 State of Hawaii Water Quality Monitoring and Assessment Report from the Hawaii Department of Health: 
https://health.hawaii.gov/cwb/files/2018/09/Final-2018-State-of-Hawaii-Water-Quality-Monitoring-Assessment-Report.pdf

##A.1. Assessment Units
The Asessment Units (AUs) used to assess consisted of points, stretches of coastline, and waters contained within two geographical locations. Hawaii Clean Water Branch watershed AUs were established for the islands of Kauai, Maui, Oahu, Lanai, and Molokai, and the marine water quality within each
CWB watershed AU was assessed if sufficient data was available during this cycle. Nearshore recreational watersare classified as coastal waters if they are within 300 meters of shoreline, and are classified as offshore waters if they are beyond 300 meters of the shoreline. 

##PART B. Assessment Methodology
Decisions for including sample information is based on the quality and quantity of data, water body type, and applicable State WQS. Numerous categories may be applicable to describe the current status of a water body because each AU is assessed for multiple pollutants. Data collected in State receiving waters are placed into the appropriate assessment unit.  AUs are assessed for recreational health and ecosystem heath, where data is available. 

### Enterococcus
Recreational health is assessed by enterococci, which is the EPA's recommended fecal indicator bacteria for coastal recreational waters. The presence of enterococci in sufficient numbers “indicates the potential for human infectious diseases” as defined in the CWA §502(23) (EPA Office of Water 2012). More specifically, it indicates the presence of human fecal contamination and pathogens. An AU is considered impaired if 5 or more samples of enterococci geometric mean(GM) in a 30-day interval exceeded 35 Colony Forming Units(CFU)/100 mL of water. The public must be notified if the enterococci concentrations in any sample exceed 130 CFU/100 mL. 

##B.2. Ecosystem Health Assessment
From the Hawaii Department of Health Administrative Rules Chapter 54: Water Quality Standards, which can be accessed here:
https://health.hawaii.gov/cwb/files/2013/04/Clean_Water_Branch_HAR_11-54_20141115.pdf

Ecosystem health assessments are based on a geometric mean calculation of the nutrient and
field parameters identified in HAR §11-54-6. Assessments require a minimum of 30 samples to be collected from State receiving waters within the CWB watershed DU over a two-year assessment cycle. The 30 samples may come from multiple stations located within the larger CWB watershed DU and should be representative of seasonal variation where possible. 

###Turbidity
Turbidity is the degree to which light is scattered by particles suspended in a liquid. Turbidity is measured in Nephelometric Turbidity Units (NTU). The measured turbidity will vary based on the light's wavelength and the angle at which the detector is positioned. The higher the intensity of the scattered light, the higher the turbidity measurement will be. Anthropogenic activities such as agriculture or construction can lead to sediments entering water bodies and will increase turbidity. Aquatic ecosystems can be negatively affected by high turbidity values over a long period of time. In Hawaii, turbidity values are not to exceed 10 NTU during the dry season (May 1st-October 31st) more than 2% of the time, and can't exceed 25 NTU during the wet season (November 1st through April 30th) more than 2% of the time. 


###pH
pH is a scale used to specify how acidic or basic a solution is. The pH scale ranges from 0-12.  According to the Hawaii Department of Health Administrative Rules Chapter 54: Water Quality Standards, "pH units shall not deviate more than 0.5 units from a value of 8.1, except at coastal locations where and when freshwater from stream, stormdrain, or groundwater may depress the pH to a minimum level of 7.0."


###Dissolved Oxygen
Dissolved Oxygen (DO) is the amount of gaseous oxygen dissolved in the water. Dissolved Oxygen is measured in mg/L. Oxygen levels in water vary from absorption from the atmosphere, as a waste product of photosynthesis, point source pollution, nutrient polution, aquatic life, and other factors. DO levels are strongly influenced by temperature and salinity. The solubility of oxygen decreases as the water’s temperature and salinity increase. DO is one of the best indicators of a water body's health.   According to the Hawaii Administrative Rules Chapter 54, DO cannot be "less than 75 percent saturation, determined as a function of ambient water temperature and salinity."

###Salinity
Salinity is a measure of the total amount of dissolved salts in a water body. The units to measure salinity are parts per thousand (ppt) or grams/kilogram (g/kg). According to the Hawaii Administrative Rules Chapter 54, Salinity "shall not vary more than 10% from natural or seasonal changes considering hydrologic input and oceanographic factors." 

###Temperature
Temperature is the Water temperature is a physical property expressing how hot or cold water is. For this dataset,Temperature is measured in degrees Celsius.  As hot and cold are both arbitrary terms, temperature can further be defined as a measurement of the average thermal energy of a substance. Water temperature affects almost every other water quality parameter including dissolved oxygen, salinity, and pH.  According to the Hawaii Administrative Rules Chapter 54, temperature "shall not vary more than one degree Celsius from ambient conditions."
