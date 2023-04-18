# geopoliticalApp

Initial datasources:

https://www.idea.int/gsod-indices/sites/default/files/inline-files/global-state-of-democracy-indices-codebook-v6.pdf
https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fwww.idea.int%2Fgsod-indices%2Fsites%2Fdefault%2Ffiles%2Finline-files%2Fgsodi_v6.1_1975_2021.xlsx&wdOrigin=BROWSELINK


https://www.imf.org/en/Publications/WEO/weo-database/2023/April/download-entire-database




-Data will be hosted in an Azure SQL server post modeling
-Azure Function apps to call endpoints from SQL server
-D365 button to call plug-in webhook



https://d365demystified.com/2020/03/19/call-azure-function-from-dynamics-365-crm-using-webhooks/




DESIGN:

Building a ASP.Net Core Web API, utilizing an Azure Web App service to call data from an Azure SQL DB.

High level Steps:

Configure Azure SQL DB with table structure, and import data using the Azure Data Factory service

