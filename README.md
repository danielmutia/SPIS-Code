# MSc-Code
Methodology for sizing solar powered irrigation systems

The following are the required inputs for the model:
country (name)
state (name - admin 1 or 2)
- lat, lon (deg)
- gw_depth (Ground water depth in m)
- sw_dist (Distance to surface water in m)
- sw_depth (elevation of the nearest surface water source)
- elevation (in m)
- awsc (Water storage capacity of the soil in mm/m)
- sw_suit_idx (Surface irrigation suitability index: 1= suitable 9999= non suitable)
- prec_i (Average precipitation in mm/month; i=1-12)
- srad_i (Average solar irradiation per month in kJ m-2 day-1; i=1-12)
- wind_i (Average wind speed per month in m s-1; i=1-12)
- tavg_i, tmax_i, tmin_i(Average, Max, Min temperature per month in C; i=1-12)
- c (effective precipitation factor)
- kc_i (Crop coefficient values at different months depending on growth calender i=1-12)
- no_access (density of people without access to electricity per km^2)
- pvout_i (Mothly PV potential in kWh/kWp)
- protected (1 if not protected and 9999 if protected)

This code outputs the following parameters for solar powered irrigation systems:
- Peak water requirements (in l/ha/day)
- Peak power demand (in kW/ha)
- PV Size (in kW/ha)
- Annual Energy Demand for Agriculture (kWh/ha)
- Electrification Potential (kWh/ha)
- Utilisation factors before and after electrification
- Cost of the system
