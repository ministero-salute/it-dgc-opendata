<h1 align="center">EU Digital Covid Certificate - Open Data</h1>

<div align="center">
<img width="256" height="256" src="img/logo-dcg.png">
</div>

<br />
<div align="center">
    <!-- CoC -->
    <a href="CODE_OF_CONDUCT.md">
      <img src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg" />
    </a>
    <!-- last commit -->
    <a href="https://github.com/ministero-salute/it-dgc-opendata/commits/master">
      <img src="https://img.shields.io/github/last-commit/ministero-salute/it-dgc-opendata" />
    </a>

</div>

# Description

This repository contains the data collected by the Italian "EU Digital Covid Certificate" system.

In particular, the following data are uploaded every day at 2 am (UTC):
- daily trend of issued and acquired EU DCC divided by categories.

Furthermore, it is possible to check the interactive visualization of this dataset on the dedicated [DGC dashboard](https://www.dgc.gov.it/spa/dashboard).

# Contents

- [Repository structure](#repository-structure)
- [Data format](#data-format)
- [Data update](#data-update)
- [License](#license)


# Repository structure
```
it-dgc-opendata/
│
├── data/
│   ├── dgc-issued.csv
│   ├── dgc-issued.json
│   ├── dgc-issued-latest.csv
│   ├── dgc-issued-latest.json
│   ├── dgc-acquired.csv
│   ├── dgc-acquired.json
│   ├── dgc-acquired-latest.csv
│   ├── dgc-acquired-latest.json
```

# Data format
- [DGC issued trend data](https://github.com/ministero-salute/it-dgc-opendata/blob/master/format-dgc-issued-trend.md)
- [DGC acquired trend data](https://github.com/ministero-salute/it-dgc-opendata/blob/master/format-dgc-acquired-trend.md)

# Data update
Daily trend data: every day at 2 am (UTC).

# Licence

## Authors / Copyright

Copyright 2021 (c) Ministero della Salute.

Please check the [AUTHORS](AUTHORS) file for extended reference.

## Third-party component licences

## Licence details

The licence for this repository is a [GNU Affero General Public Licence version 3](https://www.gnu.org/licenses/agpl-3.0.html) (SPDX: AGPL-3.0). Please see the [LICENSE](LICENSE) file for full reference.
