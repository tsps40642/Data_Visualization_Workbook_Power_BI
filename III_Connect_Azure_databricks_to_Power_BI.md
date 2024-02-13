# Connect_Azure_databricks_to_Power_BI

This page demonstrates steps to connect analytics.uofm to PowerBI.  

1. In Power BI:  
Chose Get Data -> More -> Azure -> Azure Databricks -> enter `Server Hostname` and `HTTP Path` -> choose the file under the Catalog -> chose "Azure Active Directory" and login with your credentials if needed  

2. In databricks:  
The `Server Hostname` and `HTTP Path` can be found in databricks at:  
- On LHS choose 'Compute' -> Click on the active cluster -> 'Configuration' -> 'Advanced options' dropdown -> 'JDBC/ODBC'  
