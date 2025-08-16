# RSNA Intracranial Aneurysm Detection
## Kaggle Competition URL
https://www.kaggle.com/competitions/rsna-intracranial-aneurysm-detection/data
## Story so far
* Explored the DICOM files using duckdb and polars
* Extracted metadata from all the training DICOM series via multithreading
* Appended the training metadata along with the 14 target variables using duckdb
* Saved the final dataframe containing DICOM image metadata, coordinates of aneurysm location (for applicable images), training metadata in a single parquet file
