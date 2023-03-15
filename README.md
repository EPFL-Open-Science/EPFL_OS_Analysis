# EPFL_OS_Analysis

Author: Carlos Vivar Rios [Vivar Rios Analytics](http://www.carlosvivarrios.com)
Promoters: Open Science Office (EPFL)

Exploratory analysis of open science production in repositories. 

## Structure of the project

The project consist on 3 main tasks of data exploration in Github, Open Access Monitor, and Zenodo. 

### Github EPFL Open Science community exploration

In this task the goals are: 

1. Identify users (organizations, and single users) that can be linked to EPFL
2. Identify repositories that can be related to EPFL

Once these items are identify data is enriched with custom fields of interest, such as licenses, contributors, or programming languages. 

### Zenodo EPFL Open Science repositories exploration

In this task we retrieved Zenodo repositories associated to specific badges. 

### Open Access Monitor exploration

Parse and data preparation of datasets from https://oamonitor.ch/about/

### Folder description


```bash
root/
 |-- data/
 |   |-- 16_01_2022_1_df.pickle
 |   |-- 16_01_2022_1_dfUsers.pickle
 |   |-- 16_01_2022_1_dfUsers.pickle
 |   |-- 16_01_2022_1_repos.pickle
 |   |-- 16_01_2022_1.pickle
 |   |-- 17_01_2022_1_dfUsers.pickle
 |   |-- 17_01_2022_1_reCon.pickle
 |   |-- 17_01_2022_2_dfUsers.pickle
 |   |-- 17_01_2022_2_reCon.pickle
 |   |-- 2018-2021_repo-data_ALL_2022-11-01.xlsx
 |-- resutls/
 |   |-- ...
 |-- tableau/
 |   |-- ...
 |-- 001.Github_users.ipynb
 |-- 002.Github_plots.ipynb
 |-- 003.Zenodo_analysis.ipynb
 |-- 004.Open_repository_plots.ipynb
 |-- 005.Zenodo_Community_analysis.ipynb
 |   requirements.txt
 ```

## How to run this project

Obtain Token from Github and Zenodo and place them in a `.env` file. 

```
GITHUB_TOKEN=Token <GITHUB TOKEN>
ZENODO_TOKEN=<ZENODO TOKEN>
```



## Next steps

- [ ] Turn prototype scripts into a proper code project with a nice ETL strategy. 
- [ ] Include tests
- [ ] Container
- [ ] Documentation
- [x] Add License

## LICENSE

### SCRIPT

Apache 2.0

### DATA

CC-0