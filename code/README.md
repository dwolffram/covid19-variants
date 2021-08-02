```extract_table_from_pdf.ipynb```  
Here we extract the relevant table from the [PDF reports](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html) for older data before 2021-06-23. 

```extract_table_from_excel.ipynb```  
This notebook can be used to download and process the latest data provided as an [Excel file](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Daten/VOC_VOI_Tabelle.html). Before 2021-06-23 the numbers were only reported in the above mentioned PDF reports.

```combine_tables.ipynb```  
Here we combine all processed tables and combine them into on table in long format with additional columns indicating the data version. The result is saved in ```data/sequencing_germany.csv```.


