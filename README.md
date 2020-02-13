# RBootcamp

## initial situation:

The tourist information offices in both Arosa and Lenzerheide staff their offices according to how many tourists they expect to be contacted by. The process of staffing the office relies on experience and laborious mapping of the next months events, season, holidays etc.

## client requirements:

The tourist office would like a tool to facilitate and enhance the prediction of tourist requests.

A prediction model should forecast the amount of tourist requests throughout different channels such as phone, email, and front desk per month. 

## data: 

The data set contains the following variables:
Datum	Wochentag	season	isFerienZH	Ferien Desc ZH	isFerienSG	Ferien Desc SG	isFerienGR	Ferien Desc GR	Feiertag Desc	isFeiertag ZH	isFeiertag SG	isFeiertag GR	t_2m_c_avg	snow_depth_cm_avg	visibility_m_avg	wind_speed_10m_ms_max	prob_precip_1h_p_avg	prob_tstorm_1h_p_avg	hail_idx_avg	wind_gusts_10m_ms_max	wind_speed_mean_10m_24h_ms_avg	t_max_2m_24h_c_max	t_min_2m_24h_c_min	precip_24h_mm_max	fresh_snow_24h_cm_max	is_sleet_1h_idx_max	is_fog_1h_idx_max	precip_1h_mm_sum	fresh_snow_1h_cm_sum	wind_speed_mean_10m_1h_ms_avg	weather_symbol_1h_idx_spe	number_of_events	Schalter	Tel	Mail	Total Anfragen

the variables can be grouped into the following buckets: school holidays, public holidays, season and weather. 

The time range is from 01.05.2017 - 30.09.2019

## folder structure:

|— R_Bootcamp
|—— Code (use this as working directory)
|——— RBootcamp_Assignment.Rmd
|—— DATA
|—— OUTPUT

 
 
https://hack.opendata.ch/project/375
