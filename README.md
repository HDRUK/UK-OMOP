# UK-OMOP
A directory of [OMOP CDM](https://www.ohdsi.org/data-standardization/) data sets in the UK.

The aim of this page is to create a table of OMOP projects and data sets in the UK. This table will be displayed in the [UK Health Data Research Alliance](https://ukhealthdata.org/) web pages. The aim is to signpost OMOP resources in the UK, rather than to replace sites such as the [EHDEN](https://www.ehden.eu/) [Portal](https://portal.ehden.eu/) and the [HDR Innovation Gateway](https://www.healthdatagateway.org/). The data was collected as part of a [survey of OMOP activity](https://ukhealthdata.org/projects/adoption-of-the-omop-common-data-model/) in the UK (preliminary results: report [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8309536.svg)](https://doi.org/10.5281/zenodo.8309536)
and poster [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8309722.svg)](https://doi.org/10.5281/zenodo.8309722)
). It will also be published on [Zenodo](https://zenodo.org/communities/hdruk).
The intention is that by making this accessible on GitHub that organisations can amend their own data, if desired.

This repository includes the following files:
- [Source CSV file](Combined%20Organisation%20Dataset%20Table%20(v4).csv) Exported from original Excel spreadsheet - not for display or editing
- [Processed CSV file](Dataset_Table.csv) Alternative file format for the table. Processed, for example filled forward on organisation names.
- [JSON file](datasets.json) Converted from CSV file
- [Jupyter Notebook](csv_to_json.ipynb) to convert CSV file to JSON format

The current plan is that the JSON file will be linked to from the [Alliance CDM web page](https://ukhealthdata.org/data-standards/common-data-models/). This is the version that should be edited to make any changes to the table.

Questions? Please contact [Alex Knight](mailto:alex.knight@hdruk.ac.uk) or [UK Alliance](mailto:ukalliance@hdruk.ac.uk)
