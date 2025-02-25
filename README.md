# UK-OMOP
A directory of [OMOP CDM](https://www.ohdsi.org/data-standardization/) data sets in the UK.

The aim of this page is to create a table of OMOP projects and data sets in the UK. This table will be displayed in the [UK Health Data Research Alliance](https://ukhealthdata.org/) web pages. The aim is to signpost OMOP resources in the UK, rather than to replace sites such as the [EHDEN](https://www.ehden.eu/) [Portal](https://portal.ehden.eu/) and the [HDR Innovation Gateway](https://www.healthdatagateway.org/). The data was initially collected as part of a [survey of OMOP activity](https://ukhealthdata.org/projects/adoption-of-the-omop-common-data-model/) in the UK (preliminary results: report [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8309536.svg)](https://doi.org/10.5281/zenodo.8309536)
and poster [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8309722.svg)](https://doi.org/10.5281/zenodo.8309722)
). It has also been published on [Zenodo](https://zenodo.org/communities/hdruk) with the DOI: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14800402.svg)](https://doi.org/10.5281/zenodo.14800402)

The intention is that by making this accessible on GitHub that organisations can amend their own data, if desired.

This repository includes the following files:
- [Source CSV file](Combined%20Organisation%20Dataset%20Table%20(v4).csv) Exported from original Excel spreadsheet - not for display or editing
- [Processed CSV file](Dataset_Table.csv) Alternative file format for the table. Processed, for example filled forward on organisation names.
- [JSON file](datasets.json) Converted from CSV file - probably the most straightforward file to edit.
- [Jupyter Notebook](csv_to_json.ipynb) to convert CSV file to JSON format
- [Jupyter Notebook](json_to_csv.ipynb) to convert JSON file to CSV format

This JSON file is linked to from the page [Directory of UK OMOP Data Sets](https://ukhealthdata.org/data-standards/directory-of-omop-data-sets-in-the-uk/). The JSON file should be edited to make any necessary changes to the table. Releases are linked to Zenodo and each will have their own DOI (see above).

The JSON file contains the following fields, each of which forms a column in the directory table on the web site. Each entry should contain these fields:

|Field|Description|Example|
|-----|-----------|-------|
|`Organisation name`|A link to the data custodian web site and their name, separated by a double pipe: `\|\|` |_"[https://alleviate.ac.uk\|\|Alleviate Hub](https://alleviate.ac.uk)"_|
|`Data set`|The name or acronym of the data set|_"Birmingham Inflammation and joint pain study"_|
|`Care type`|The tier of care or type of research, e.g. primary care, registry.|_"Secondary care"_|
|`Health area`|The field of health care the data applies to, e.g. "Cancer" or "General"|_"Pain"_|
|`Link`|A link to the data set on a portal or repository. Include the portal name after a double pipe.|_"[https://healthdatagateway.org/en/dataset/1009\|\|Gateway](https://healthdatagateway.org/en/dataset/1009)"_|

Please take care with your JSON formatting!

Questions? Please contact [Alex Knight](mailto:alex.knight@hdruk.ac.uk) or the [Data Standards team](mailto:data_standards@hdruk.ac.uk)
