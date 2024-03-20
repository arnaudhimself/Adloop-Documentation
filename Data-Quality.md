
## General warning about imported data


Adloop connects to  **Data Sources**  set up in a  **Dataset**  to import the required  **Dimensions**  and  **Metrics** .

We guarantee to keep the APIs active and up to date with Platform recommendations. However, the rights to connect to the Data Sources and the quality of the source data depend exclusively on the Platforms themselves and the validity of the access rights.


## Frequency of data import


Adloop connects to the Platforms  **every 3 hours**  to retrieve the freshest data.

It is important to be aware that the data retrieved during the day is far from exhaustive because the processes are ongoing. They can change from one minute to the next.


## Completeness of the data imported from the Platforms
The Platforms perform many consolidation and control operations to communicate complete data as soon as possible. However, sometimes technical incidents or slowdowns have affected the ongoing processes.

To be sure of the quality of the imported data, Adloop performs a data quality control on  **D+1** ,  **D+3**  and finally  **D+7** . This means that the data may change slightly over a period of 7 days.

Rest assured, these changes are usually minor: a few impressions, a few cents .... Nothing that affects past analysis.


## Currency conversion when importing
To standardize currencies in Adloop, we perform conversions from the  **Data Source**  currency to the currency chosen for the  **Dataset**  on import.

Our source for conversion rates is [XE.com](http://XE.com), the world's leading expert on the matter.

Since we perform conversions on a daily basis, we are dependent on changes in exchange rates. As a result, the currency metrics you see in Adloop may differ from the amounts offered in some platforms (for example, for billing).



*****

[[category.storage-team]] 
[[category.confluence]] 
