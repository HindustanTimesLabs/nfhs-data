# Data from National Family Health Survey 4, 2015-16

Scraped from PDFs hosted on the [International Institute for Population Sciences website](http://rchiips.org/NFHS/districtfactsheet_NFHS-4.shtml). Here are examples of [a district-wise PDF](http://rchiips.org/NFHS/FCTS/AN/Nicobars.pdf) and [a state-wise PDF](http://rchiips.org/NFHS/pdf/NFHS4/AN_FactSheet.pdf).

### District-wise data
**[`nfhs_district-wise.csv`](https://github.com/HindustanTimesLabs/nfhs-data/blob/master/nfhs_district-wise.csv)** has district-wise data for all 93 indicators that are applicable at the district level.

That file is 6.7 MB in size. If you would prefer to work with smaller files, each indicator has its own CSV file in the **[`indicator-wise`](https://github.com/HindustanTimesLabs/nfhs-data/tree/master/indicator-wise)** directory. Each file is named according to the number of the indicator of the data it contains. To look up which number corresponds to which indicator, see the file **[`nfs_indicator_lookup.csv`](https://github.com/HindustanTimesLabs/nfhs-data/blob/master/nfhs_indicator_lookup.csv)**.

### State-wise data
**[`nfs_state-wise.csv`](https://github.com/HindustanTimesLabs/nfhs-data/blob/master/nfhs_state-wise.csv)** has state-wise data for all 114 indicators that are applicable at the state level.