# Tanzania-well-analysis
This analysis is based on the competition Driven Data® published about water pumps in Tanzania. The competition information was obtained by the Tanzania Ministry of Water using an open-source platform called Taarifa. Tanzania is the largest country in East Africa, with a population of about 60 million. Half of the population does not have access to clean water, and 2/3 of the population suffers from poor sanitation. In poor households, families often have to spend several hours walking to obtain water from water pumps. Billions of dollars in foreign aid are being provided to Tanzania to tackle the freshwater problem. However, the Tanzanian government cannot solve this problem. A significant part of water pumps are entirely out of order or do not function; the others require repair. Tanzania’s Ministry of Water Resources agreed with Taarifa, and they launched the DrivenData competition. 

## Data
The data has many characteristics associated with water pumps. Data related to geographical locations, organizations that create and manage them, and some data about the region, local government areas. Also, there is information on the types of checkouts, types and number of payments. The water supply points were divided into functional, non-functional and functional but in need of repair. The goal of the competition is to build a model that predicts the functionality of water supply points.

## Data Fields
The following set of information about waterpoints is presented for analysis:
amount_tsh — Total static head (amount water available to waterpoint)
date_recorded — The date the row was entered
funder — Who funded the well
gps_height — Altitude of the well
installer — Organization that installed the well
longitude — GPS coordinate
latitude — GPS coordinate
wpt_name — Name of the waterpoint if there is one
num_private — No information
basin — Geographic water basin
subvillage — Geographic location
region — Geographic location
region_code — Geographic location (coded)
district_code — Geographic location (coded)
lga — Geographic location
ward — Geographic location
population — Population around the well
public_meeting — True/False
recorded_by — Group entering this row of data
scheme_management — Who operates the waterpoint
scheme_name — Who operates the waterpoint
permit — If the waterpoint is permitted
construction_year — Year the waterpoint was constructed
extraction_type — The kind of extraction the waterpoint uses
extraction_type_group — The kind of extraction the waterpoint uses
extraction_type_class — The kind of extraction the waterpoint uses
management — How the waterpoint is managed
management_group — How the waterpoint is managed
payment — What the water costs
payment_type — What the water costs
water_quality — The quality of the water
quality_group — The quality of the water
quantity — The quantity of water
quantity_group — The quantity of water (duplicates quality)
source — The source of the water
source_type — The source of the water
source_class — The source of the water
waterpoint_type — The kind of waterpoint
waterpoint_type_group — The kind of waterpoint

Information quoted from Taras Baranyuk https://towardsdatascience.com/pump-it-up-with-catboost-828bf9eaac68