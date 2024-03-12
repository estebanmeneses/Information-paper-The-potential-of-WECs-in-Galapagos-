# Information-paper-The potential of Wave Energy Converters in the Galapagos Islands-
This repo contains all data and its sources to replicate the results of the paper: "The potential of wave energy converters (WEC) for the long-term energy transition of the Galapagos Islands"

# Abstract 

Wave energy converters (WEC) are one of the options for the long-term decarbonization in the Galapagos islands. However, its energy potential has not yet been studied. This work estimates the
different levels of WEC energy potential: gross, sustainable and tecno-economic. To assess the WEC long-term techno-economic potential, by island, an application for Galapagos of the OSeMOSYS
energy planning model is developed. The results show that WECs have significant energy potential in the Galapagos, with a gross potential of 262 TWh/year, a sustainable potential of 25TWh/year
and a technical potential varying between 92 and 152 MWh/year, in a WEC development longterm scenario. However, WECs are currently less economically competitive than other electricity
production technologies based on renewable energy sources, such as solar photovoltaics and wind. For instance, WECs have the highest levelized cost of electricity (LCOE) (52 ct.USD/kWh) at the
beginning of the period and (26 ct.USD/kWh) by the end of the period. Furthermore, in the WEC scenario (without subsidies), the mean generation cost increases in comparison to the reference
scenario, this difference across all islands is 1.2 USD cents in 2030, and 3.8 cents in 2050. Thus, its economic potential still depends on specific energy, industrial and environmental policies.

# Data

## OSeMOSYS Galapagos Results

There are 4 scenarios, each one with and without diesel subsidies:

- **Reference Scenario (REF)**: Thermal energy continues to predominate, with no major investment in renewable energy. New renewable energy capacity is added gradually, leading to 50% of clean energy in the power sector by 2050. This scenario is inspired by the historical information and sectorial structure up to the base year.
- **Solar and Wind (S&W) scenario**: Large investment is made in solar and wind energy, leading to 75% of clean energy in the power sector by 2030 and 100% by 2040. This scenario is inspired by the official energy transition scenario for the islands.
- **Wave Wind Solar (WWS) scenario**: Large investment is made in wave, wind, and solar energy to achieve 100% clean energy in the power sector by 2040, adding a total of 20 MW exogenously defined WECs installed capacity by 2050.
- **Wave Wind Solar and electric transport (WWSeT) scenario**: In addition to the WWS scenario, this scenario includes a larger expansion of power installed capacity due to a high electrification rate of land transport in
the islands in 7 MW by 2050. This higher final electricity demand is exogenously calculated by Bariloche (2018).

  Note: All csv files resulting from the OSeMOSYS model are found in the **OSeMOSYS_Results** folder named according to the names of the scenarios.
