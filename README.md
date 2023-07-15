# Methodology for sizing solar powered irrigation systems
The code input should be in the form of a CSV file with the rows representing the analysis polygons and the columns containing the following parameters:
- country (name)
- state (name - admin 1 or 2)
- lat, lon (deg)
- gw_depth (Ground water depth in m)
- sw_dist (Distance to surface water in m)
- sw_depth (elevation of the nearest surface water source)
- elevation (in m)
- awsc (Water storage capacity of the soil in mm/m)
- prec_i (Average precipitation in mm/month; i=1-12)
- srad_i (Average solar irradiation per month in kJ m-2 day-1; i=1-12)
- wind_i (Average wind speed per month in m s-1; i=1-12)
- tavg_i, tmax_i, tmin_i(Average, Max, Min temperature per month in C; i=1-12)
- c (effective precipitation factor)
- kc_i (Crop coefficient values at different months depending on growth calender i=1-12)
- no_access (density of people without access to electricity per km^2)
- pvout_i (Mothly PV potential in kWh/kWp)
- protected (1 if not protected and 9999 if protected)


This code outputs the parameters shown below for solar powered irrigation systems. However, more can be obtained from the code by adjusting output section of the code.
- Peak water requirements (in l/ha/day)
- Peak power demand (in kW/ha)
- PV Size (in kW/ha)
- Annual Energy Demand for Agriculture (kWh/ha)
- Total Annual Energy by the PV system
- SPIS utilisation factors
- Number of households that can be electrified from excess energy
- New SPIS utilisation factors if used for electrification
- SPIS cost

Input and output files for Kenya's average and drought scenarios analysis have been provided. You can generate and run your input file for the geography you are interested in.
