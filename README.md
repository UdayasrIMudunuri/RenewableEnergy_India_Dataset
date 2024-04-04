1. Dataset Structure:
The dataset comprises 32 files in .xlsx format. 31 excel files for each Indian State/UT data and 1 integrated file of all Indian States/UTs.
Each file contains 61 rows representing data for different states and 22 columns representing various variables.
2. Variables:
Renewable Energy Generation Capacities:
Solar Power
Wind
Biomass
Small Hydro
Meteorological Parameters:
Air Temperature
Albedo
Clearsky Direct Horizontal Irradiance (DHI)
Clearsky Direct Normal Irradiance (DNI)
Clearsky Global Tilted Irradiance (GTI)
Cloud Opacity
Direct Normal Irradiance (DNI)
Global Horizontal Irradiance (GHI)
Global Tilted Irradiance (GTI)
Precipitation Rate
Relative Humidity
Surface Pressure
Wind Speed (100m)
3. Sources:
Renewable energy capacity data sourced from authoritative sources such as the Central Electricity Authority (CEA).
Meteorological data obtained from platforms like Tutiempo.net, Weatherandclimate.com, IMD Pune, Solcast.com, and Timeanddate.com.
4. Preprocessing Steps:
Stage 1: Utilized VLOOKUP and transpose functions in Excel to modify year-wise data into state-wise data.
Stage 4: Python code was used to convert hourly meteorological data from 2019 to 2023 into monthly data for integration with remaining monthly data.
This documentation provides users with essential information about the dataset's structure, variables, sources, and preprocessing steps, enabling them to understand and utilize the dataset effectively for their analysis and research purposes.
