# ⚡ awesome-energy-tools
The main goals of this repository are:
1. Create a central hub of datasets and tools tailored for energy practitioners with intermediate programming skills. 
2. Facilitate energy research efforts and collaboration

The foundation of this repository is inspired by the excellent paper of Hussain Kazmi, Íngrid Munné-Collabo, Fahad Mehmood, Tahir Abbas Syed and Johan Driesen:

[Towards data-driven energy communities:
a review of open-source datasets, models and tool](https://doi.org/10.1016/j.rser.2021.111290)

## 🔍 Research Gaps
- Heat Data
- Transportation/Mobility Data
- Data Geographical discrepancy

## ⌚ Todo
- Mention Research gap
- Write a short description for each source
- Look in [Figshare](https://figshare.com) for new datasets
- Look in [Havard Datavers](https://dataverse.harvard.edu/) for new datasets
- Look in [OFS Home](https://osf.io/) for new datasets
- Look in [Zenodo](https://zenodo.org/) for new datasets
- Look in [Kaggle](https://www.kaggle.com/) for new datasets

## ⚠️ Important to Mention
[OPSD](https://open-power-system-data.org/)

[PyPSA](https://github.com/PyPSA)

[OPT: Open Energy Transition](https://openenergytransition.org/)

[Open Energy Platform](https://openenergy-platform.org/dataedit/schemas)

[Global Energy Monitor](https://globalenergymonitor.org/)

## Missing Data
✔️: Dataset is available
❌: Dataset not found

## Contents

- [Datasets](#datasets)
    1. [Electricity-Demand](#electicity-demand)
    2. [Heat-Demand](#heat-demand)
    3. [Weather-Climate](#weather-climate)
    4. [Photovoltaic](#photovoltaic)
    5. [Wind-Turbine](#wind-turbine)
- [Tools-Models](#tools-models)
    1. [Electricity_Generation](#electricity_generation)
    2. [Electricity_Demand](#electicity_demand)
    3. [Electricity_Demand](#electicity_demand)
    4. [Storage](#storage)
    5. [Heat_Demand](#heat_demand)
    6. [Building-System-Simulation](#building-system-simulation)
    7. [Power-Systems-Grid-Simulation](#power-systems-grid-simulation)
    8. [Optimization](#optimization)
- [Visualization](#visualization)
- [Miscellanous](#miscellanous)
- [Papers](#papers)

## Datasets

### Electricity-Demand
#### Residential Buildings
| Dataset name | Country  | Sites | Duration | Resolution |
|--------------|----------|-------|----------|------------|
| ✔️[EMBED](http://embed-dataset.org/) | US       | 3     | 2-4 weeks| 12 kHz (I, V), 1-2 Hz (plug loads) |
| ❌[REDD](https://www.reddit.com/r/datasets/comments/11mtihj/redd_a_public_data_set_for_energy_disaggregation/?rdt=34674)| US       | 6     | 2-4 weeks| 15 kHz (P, V); 0.5-1 Hz (NILM data at plug/circuit level) |
| ❌[BLUED](https://tokhub.github.io/dbecd/links/Blued.html)| US       | 1     | 1 week   | 12 kHz (I, V) |
| ✔️[PLAID](https://figshare.com/articles/dataset/PLAID_-_A_Voltage_and_Current_Measurement_Dataset_for_Plug_Load_Appliance_Identification_in_Households/10084619) | US       | 56    | Summer 2013 and winter 2014 | 30 kHz (I, V) |
| ❌[ADRES](https://publik.tuwien.ac.at/files/PubDat_178659.pdf) | Austria  | 30    | 2 weeks  | 1 Hz |
| ✔️[REFIT](https://pureportal.strath.ac.uk/en/datasets/refit-electrical-load-measurements-cleaned) | UK       | 20    | 2 years  | 0.125 Hz |
| ✔️[UK-DALE](https://jack-kelly.com/data/) | UK       | 5     | 4 years  | 16 kHz (I, V in 3 buildings); 0.17 Hz (appliance-level demand) |
| ✔️[DRED](https://www.st.ewi.tudelft.nl/~akshay/dred/) | The Netherlands | 1 |                     | 6 months | 1 Hz (energy demand); 1 minute (ambient conditions) |
| ✔️[Dataport](https://github.com/Pecan-Street/DataPort-Examples) | US       | 1400+ | 4 years  | 1 Hz, 1 minute, 15 minutes |
| ✔️[Smart*](https://traces.cs.umass.edu/index.php/smart/smart) | US       | 3     | 3 weeks  | 1 Hz |
| ✔️[AMPds](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FIE0S4) | Canada   | 1     | 2 years  | 1 minute |
| ✔️[ECODS](https://vs.inf.ethz.ch/res/show.html?what=eco-data) | Switzerland | 6 | 8 months | 1 Hz |
| ✔️[PRECON](https://web.lums.edu.pk/~eig/precon.html)| Germany  | 11    | 3 years  | 1 minute |
| ✔️[CoSSMic](https://data.open-power-system-data.org/household_data/)| Germany  | 11    | 3 years  | 1 minute |
| ✔️[ENERTALK](https://github.com/ch-shin/ENERTALK-dataset)| South Korea | 22 | 29-122 days | 15 Hz |
| ✔️[SustData](https://osf.io/2ac8q/)| Portugal | 50    | 1144 days | 2 - 10 Hz |

#### Commercial Buildings

| Dataset name    | Country        | Sites                        | Duration    | Resolution |
|-----------------|----------------|------------------------------|-------------|------------|
| ✔️[BLOND](https://zenodo.org/records/838974)       | Germany        | Office/lab                   | 50-230 days | Aggregate: 50-250 kHz, Individual (appliance-level) 6.4 kHz |
| ✔️[I-BLEND](https://springernature.figshare.com/collections/I-BLEND_a_campus_scale_commercial_and_residential_buildings_electrical_energy_dataset/3893581/1)     | India          | University                   | 52 months   | 1 minute (load); 10 minutes (occupancy) |
| ✔️[COMBED](https://combed.github.io/)      | India          | University                   | 7+ years    | 0.5 minutes |
| ✔️[Building Data Genome](https://github.com/buds-lab/the-building-data-genome-project) | US, UK, Australia | 500 (offices, universities, commercial) | 1 year | Hourly |
| ✔️[ASHRAE](https://www.kaggle.com/c/ashrae-energy-prediction)      | Worldwide      | 1449                         | 3 year      | Hourly |
| ❌[IEEE PES]()    | Multiple       | Multiple                     | Multiple    | Multiple |

#### Electric Vehicle
- ✔️[ElaadNL](https://platform.elaad.io/analyses/ElaadNL_opendata.php) 

#### Map and Stats

### Heat-Demand
- ✔️[CU-BEMS](https://www.kaggle.com/datasets/claytonmiller/cubems-smart-building-energy-and-iaq-data)

### Weather-Climate

### Photovoltaic

### Wind-Turbine

### Electricity Generation & Access
- ✔️[AfrPowerOS](https://github.com/kawacukennedy/afrpoweros) - Open dataset tracking civilian nuclear and energy infrastructure programs across all 54 African countries: IAEA Milestone phases, regulators, installed capacity, generation mix, and electricity access, with source-cited records and confidence labels.

## Tools-Models
### Electricity_Generation
- [PVGIS](https://re.jrc.ec.europa.eu/pvg_tools/en/)
- [NREL PVWatts](https://pvwatts.nrel.gov/index.php)
- [PVLIB - Python](https://pvlib-python.readthedocs.io/en/stable/)
- [Renewables.ninja](https://www.renewables.ninja/)
- [PyPSA atlite](https://github.com/PyPSA/atlite)
- [feedinlib](https://github.com/oemof/feedinlib) 

### Electricity_Demand
- [Load Profile Generator (LPG)](https://www.loadprofilegenerator.de/)
- [Artificial Load Profile Generator (ALPG)](https://github.com/utwente-energy/alpg)
- [demandlib](https://github.com/oemof/demandlib)

### Storage

### Heat_Demand
- [Demand.ninja](https://demand.ninja/)

### Bulding-Systems-Simulation

### Power-systems-grid-simulation

### Optimization

## Visualization

## Forecasting

## Papers