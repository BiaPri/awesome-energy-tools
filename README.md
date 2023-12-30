# ⚡ awesome-energy-tools
The main goals of this repository are as follows:
1. Create a central hub of datasets and tools tailored for energy practitioners with intermediate programming skills. 
2. Facilitate energy research efforts and collaboration

The foundation of this repository is inspired by the excellent paper of Hussain Kazmi, Íngrid Munné-Collabo, Fahad Mehmood, Tahir Abbas Syed and Johan Driesen:

[Towards data-driven energy communities:
a review of open-source datasets, models and tool](https://doi.org/10.1016/j.rser.2021.111290)

## Important to Mention
[OPSD](https://open-power-system-data.org/)

[PyPSA](https://github.com/PyPSA)

## Todo:
- Mention Research gap
- Look in [Figshare](https://figshare.com) for new datasets
- Look in [Havard Datavers](https://dataverse.harvard.edu/) for new datasets


## Contents

- [Datasets](#datasets)
    1. [Electricity-Demand](#electicity-demand)
    2. [Heat-Demand](#heat-demand)
    3. [Weather-Climate](#weather-climate)
- [Tools-Models](#tools-models)
- [Optimization](#optimization)
- [Visualization](#visualization)
- [Forecasting](#forecasting)
- [Papers](#papers)

## Datasets

### Electricity-Demand
#### Residential Buildings
| Dataset name | Country  | Sites | Duration | Resolution |
|--------------|----------|-------|----------|------------|
| EMBED        | US       | 3     | 2-4 weeks| 12 kHz (I, V), 1-2 Hz (plug loads) |
| REDD         | US       | 6     | 2-4 weeks| 15 kHz (P, V); 0.5-1 Hz (NILM data at plug/circuit level) |
| BLUED        | US       | 1     | 1 week   | 12 kHz (I, V) |
| PLAID        | US       | 56    | Summer 2013 and winter 2014 | 30 kHz (I, V) |
| ADRES        | Austria  | 30    | 2 weeks  | 1 Hz |
| REFIT        | UK       | 20    | 2 years  | 0.125 Hz |
| UK-DALE      | UK       | 5     | 4 years  | 16 kHz (I, V in 3 buildings); 0.17 Hz (appliance-level demand) |
| DRED         | The Netherlands | 1 |                     | 6 months | 1 Hz (energy demand); 1 minute (ambient conditions) |
| Dataport     | US       | 1400+ | 4 years  | 1 Hz, 1 minute, 15 minutes |
| Smart*       | US       | 3     | 3 weeks  | 1 Hz |
| AMPds        | Canada   | 1     | 2 years  | 1 minute |
| ECODS          | Switzerland | 6 | 8 months | 1 Hz |
| PRECON       | Germany  | 11    | 3 years  | 1 minute |
| CoSSMic      | Germany  | 11    | 3 years  | 1 minute |
| ENERTALK     | South Korea | 22 | 29-122 days | 15 Hz |
| SustData     | Portugal | 50    | 1144 days | 2 - 10 Hz |

- ✔️[EMBED](http://embed-dataset.org/)
- ❌[REDD](https://www.reddit.com/r/datasets/comments/11mtihj/redd_a_public_data_set_for_energy_disaggregation/?rdt=34674) 
- ❌[BLUED](https://tokhub.github.io/dbecd/links/Blued.html) 
- ✔️[PLAID](https://figshare.com/articles/dataset/PLAID_-_A_Voltage_and_Current_Measurement_Dataset_for_Plug_Load_Appliance_Identification_in_Households/10084619) 
- ❌[ADRES](https://publik.tuwien.ac.at/files/PubDat_178659.pdf) 
- ✔️[REFIT](https://pureportal.strath.ac.uk/en/datasets/refit-electrical-load-measurements-cleaned) 
- ✔️[UK-DALE](https://jack-kelly.com/data/) 
- ✔️[DRED](https://www.st.ewi.tudelft.nl/~akshay/dred/) 
- ✔️[Dataport](https://github.com/Pecan-Street/DataPort-Examples) 
- ✔️[Smart*](https://traces.cs.umass.edu/index.php/smart/smart) 
- ✔️[AMPds](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FIE0S4)
- ✔️[ECODS](https://vs.inf.ethz.ch/res/show.html?what=eco-data)
- ✔️[PRECON](https://web.lums.edu.pk/~eig/precon.html)
- ✔️[CoSSMic](https://data.open-power-system-data.org/household_data/)
- [ENERTALK]()
- [SustData]()

#### Commercial Buildings

| Dataset name    | Country        | Sites                        | Duration    | Resolution |
|-----------------|----------------|------------------------------|-------------|------------|
| BLOND           | Germany        | Office/lab                   | 50-230 days | Aggregate: 50-250 kHz, Individual (appliance-level) 6.4 kHz |
| I-BLEND         | India          | University                   | 52 months   | 1 minute (load); 10 minutes (occupancy) |
| COMBED          | India          | University                   | 7+ years    | 0.5 minutes |
| Building Data Genome | US, UK, Australia | 500 (offices, universities, commercial) | 1 year | Hourly |
| ASHRAE          | Worldwide      | 1449                         | 3 year      | Hourly |
| IEEE PES        | Multiple       | Multiple                     | Multiple    | Multiple |

- [BLOND]()
- [I-BLEND]() 
- [COMBED]() 
- [Building Data Genome]() 
- [ASHRAE]() 
- [IEEE PES]() 

#### Map and Stats

## Heat-Demand

## Weather-Climate

## Tools-Models

## Optimization

## Visualization

## Forecasting

## Papers