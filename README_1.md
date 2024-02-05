# Power_BI_Tips_and_Tricks

This is a notebook for tips and tricks of data visualization on Microsoft Power BI.  
Below are demonstrations for some steps using sample dataset from: https://youtu.be/PnfrhEcwxdw?si=SkxGOK0JrgjTF0Bc  

## Generate result from Q&A in AI visual 
1. Click "Insert" -> click "Q&A" (in AI visual category) -> type the query you want to know
2. I entered "Show me te customer name with total revenue as a pie chart" -> right click "setting" -> can see other options
3. If I want to preserve the generated chart, click "turn this Q&A result into a standard visual"

## Summarize data using Smart narrative in AI visual 
1. Click "Insert" -> click "smart narrative" (in AI visual category) -> automatic summary of data

## Preview Features 
1. Click "File" -> "Options and settings" -> "Options" -> "Preview Features" on the RHS
2. Select or unselect the features

## Further analysis tool 
Can add additional analysis to the visuals to make sense of them  
1. Select a visual
2. On the RHS click "Add further anaysis to your visual" -> add analysis you want, the following are some common features  
   (1) Turn on "Trend line"   
   (2) Turn on "Forecast", can modify seasonality, CI, etc.  
   (3) Turn on "Find anomalies", can modify sensitivity -> click on an anomaly to see its information

## Custom visuals
1. Click "..." in "Visualizations" on the RHS -> click "get more visual"
2. Click "Text Filter" and drag Customer Name, so we can use Customer Name as a filter

## Filter 
1. Click "Slicer" to change the filter form in the previous section  
2. Click "Format your visual" can change the form of the filter
3. If you want to apply the filter to one or multiple pages, expand the "Filters" -> drag Customer Name to "Filters on this page" to apply filters  
4. Click the eye on top-right so after publishing, users can't modify the filters

## Microsoft Teams
1. Click "Publish" -> select "My workspace" to publish
2. Go to Teams -> go to the channel you want to place -> click "+" -> Search "Power BI" -> click "save"
3. Click "Browse workspaces" -> go to "My Workspace" -> select your report -> "Add" -> it appears on the tab on the top

## Data preview
1. Go to Power BI web surface -> select the chart you want and click "pin visual"
2. Go to dashboard and you can see, dashboard allows you to put multiple metrics from different report in the same place

## Dashboards 
Can drag charts from different report and put them together  

## Set alerts
1. Click the metric in dashboard -> click "manage alert" -> click "add alert rule"
2. By setting "Condition", "Threshold", "Max. nitification freq.", you can receive an alert when the value of that metric exceed/drop below the threshold

## Subscriptions
It will send report to designated members with the frequency set  

## Wallpapers  
Under "Vsualization" click "Format your report page" -> customize your report  
