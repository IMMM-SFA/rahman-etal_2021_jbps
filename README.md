_your zenodo badge here_

# rahman-etal_2021_jbps

**Methodology and Analytical Approach to Investigate the Impact of Building Temperature Setpoints**

Aowabin Rahman<sup>1\*</sup>, Amanda D. Smith<sup>1</sup>, YuLong Xie<sup>1</sup>, Jermy V. Thomas<sup>1</sup>, Casey D. Burleyson<sup>1</sup>

<sup>1 </sup> Pacific Northwest National Laboratory, Richland, Washington, USA

\* corresponding author:  aowabin.rahman@pnnl.gov

## Abstract
This paper presents a method for generating a large set of stochastically varying temperature setpoint schedules for EnergyPlus building performance simulations. It analyzes tradeoffs resulting from specific changes to those schedules in terms of three quantities: total electricity consumption per day; maximum hourly electricity consumption per day; and predicted percentage dissatisfied (occupant thermal comfort). The method for generating schedules requires a single base schedule as the starting point and, using a few clearly dened parameters, transforms it into a set of schedules that can be used for modeling an existing building stock or for performing parametric studies. Temperature setpoint schedules are generated and simulated for a small office building in a cool-dry climate in three different case studies pertaining to changing temperature setpoint schedules. Tradeoffs between the three output metrics are significant and vary based on the temperature setpoint schedules and the time of the year.

## Journal reference
<fill in when available>

## Code reference

Rahman, A., & Vernon, C. R. (2021, June 17). IMMM-SFA/tempset: v0.0.0 (Version v0.0.0). Zenodo. http://doi.org/10.5281/zenodo.4976805

## Data reference

### Input data
Reference for each minted data source for your input data.  For example:

Human, I.M. (2021). My input dataset name [Data set]. DataHub. https://doi.org/some-doi-number

### Output data
Reference for each minted data source for your output data.  For example:

Human, I.M. (2021). My output dataset name [Data set]. DataHub. https://doi.org/some-doi-number

## Contributing modeling software
| Model | Version | Repository Link | DOI |
|-------|---------|-----------------|-----|
| model 1 | version | link to code repository | link to DOI dataset |
| model 2 | version | link to code repository | link to DOI dataset |
| component 1 | version | link to code repository | link to DOI dataset |

## Reproduce my experiment
Fill in detailed info here or link to other documentation that is a thorough walkthrough of how to use what is in this repository to reproduce your experiment.


1. Install the software components required to conduct the experiement from [Contributing modeling software](#contributing-modeling-software)
2. Download and install the supporting input data required to conduct the experiement from [Input data](#input-data)
3. Run the following scripts in the `workflow` directory to re-create this experiment:

| Script Name | Description | How to Run |
| --- | --- | --- |
| `step_one.py` | Script to run the first part of my experiment | `python3 step_one.py -f /path/to/inputdata/file_one.csv` |
| `step_two.py` | Script to run the last part of my experiment | `python3 step_two.py -o /path/to/my/outputdir` |

4. Download and unzip the output data from my experiment [Output data](#output-data)
5. Run the following scripts in the `workflow` directory to compare my outputs to those from the publication

| Script Name | Description | How to Run |
| --- | --- | --- |
| `compare.py` | Script to compare my outputs to the original | `python3 compare.py --orig /path/to/original/data.csv --new /path/to/new/data.csv` |

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Script Name | Description | How to Run |
| --- | --- | --- |
| `generate_figures.py` | Script to generate my figures | `python3 generate_figures.py -i /path/to/inputs -o /path/to/outuptdir` |
