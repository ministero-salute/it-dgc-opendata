# DGC issued daily trend data format

## Data update
- Every day at 2 am (UTC). 

## Data format

**Reference file:** dgc-issued.csv<br>

| Field Name                  | Description (ITA)                       | Description                            | Format                       | Example             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                    | Data di riferimento            | reference data                   | YYYY-MM-DD | 2021-06-17 |
| **issued_for_vaccines**     | numero di DGC giornalieri emessi da vaccinazione | number of daily DGC issued by vaccination           |  number     |         3         |
| **issued_for_tests**        | numero di DGC giornalieri emessi da test covid-19 (tampone) | number of daily DGC issued per covid-19 test        |  number                        | 3                  |
| **issued_for_healing**      | numero di DGC giornalieri emessi da guarigione dal covid-19        | number of daily DGC issued by covid-19 healing                     | number             | 3             |
| **issued_all**              | numero totale di DGC giornalieri emessi             | total number of daily DGC issued                                  | number                         | 3          |

For each field there is also an additional field (_total) which contains the total number of DGC issued calculated as a cumulative sum starting from the beginning.

These data are also available in a json format.

### Note
No