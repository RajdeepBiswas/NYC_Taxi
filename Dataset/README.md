This folder will contain 3 datasets used for the purpose of this analysis.

1. NYC Taxi & Limousine Commission - yellow taxi trip records. This dataset is stored in Parquet format. There are about 1.5B rows (50GB) in total as of 2018.This dataset contains historical records accumulated from 2009 to 2018.
2. Worldwide public holiday data sourced from PyPI holidays package and Wikipedia, covering 38 countries or regions from 1970 to 2099. This dataset is stored in Parquet format. It is a snapshot with holiday information from 1970-01-01 to 2099-01-01. The data size is about 500KB.
3. Worldwide hourly weather history data (example: temperature, precipitation, wind) sourced from the National Oceanic and Atmospheric Administration (NOAA).This dataset is stored in Parquet format. It is updated daily, and contains about 400M rows (20GB) in total as of 2019.This dataset contains historical records accumulated from 2008 to the present.

The dataset is pulled from Azure Open Datasets which are hosted in the Azure Blob storage which provides a scalable, cost-efficient object storage in the cloud.
For quick review purpose we have kept the first 1000 records from each dataset.


Ref:
<https://azure.microsoft.com/en-us/services/open-datasets/>
<https://azure.microsoft.com/en-us/services/storage/blobs/>

