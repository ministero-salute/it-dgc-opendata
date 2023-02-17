# DGC acquired daily trend data format

## Data update
- Every day at 2 am (UTC). 

## Data format

**Reference file:** dgc-acquired.csv<br>

| Field Name                  | Description (ITA)                       | Description                            | Format                       | Example             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                    | data di riferimento            | reference date                   | YYYY-MM-DD | 2021-06-17 |
| **acquired_by_app_immuni**  | numero giornaliero di DGC acquisiti tramite l'app "Immuni" | daily number of DGC acquired through the "Immuni" app      |  number     |         3         |
| **acquired_by_web_ts**      | numero giornaliero di DGC acquisiti tramite portale il portale dgc.gov.it utilizzando la tessera sanitaria | daily number of DGC acquired through the portal dgc.gov.it using the "Tessera Sanitaria" |  number                        | 3                  |
| **acquired_by_web_id**      | numero giornaliero di DGC acquisiti tramite portale il portale dgc.gov.it utilizzando un documento di riconoscimento| daily number of DGC acquired through the portal dgc.gov.it using the identification document | number             | 3             |
| **acquired_by_web_spid**    | numero giornaliero di DGC acquisiti tramite portale il portale dgc.gov.it utilizzando SPID | daily number of DGC acquired through the portal dgc.gov.it using SPID | number                         | 3          |
| **acquired_by_operator_ts** | numero giornaliero di DGC acquisiti tramite operatore utilizzando la tessera sanitaria | daily number of DGC acquired through the operator using the "Tessera Sanitaria" | number                         | 3          |
| **acquired_by_operator_id** | numero giornaliero di DGC acquisiti tramite operatore utilizzando un documento di riconoscimento | daily number of DGC acquired through the operator using the identification document | number                         | 3          |
| **acquired_by_app_io**      | numero giornaliero di DGC acquisiti tramite l'app "IO" | daily number of DGC acquired through the "IO" app | number                         | 3          |
| **acquired_all**            | numero giornaliero di DGC acquisiti complessivamente | daily number of DGC acquired overall | number                         | 3          |

For each field there is also an additional field (_total) which contains the total number of DGC acquired calculated as a cumulative sum starting from the beginning.

These data are also available in a json format.

### Note
No
