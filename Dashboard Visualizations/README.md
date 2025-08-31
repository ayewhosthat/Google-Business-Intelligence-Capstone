## Step 3 - Visualizations
After having finished the planning documents and obtained the relevant data using an ETL pipeline, we've now been asked to create a series of dashboards for the Cyclistic product development team. In particular, they have a few specific goals in mind for visualizations:
- Understand what customers want, what makes a successful product, and how new stations might alleviate demand in different geographical areas
- Understand how the current line of bikes are used
- Apply customer usage insights to inform new station growth
- Understand how different users (subscribers and non-subscribers) use the bikes

### 1. Connect datasets to Tableau
As the query results were saved as BigQuery tables, they were then exported to Google Drive to allow for Tableau to connect directly through its Google Drive connector. 
### 2. Create dashboard mockups
After the dataset was loaded into Tableau, a mockup (or sketch) of what each dashboard should look like was made to guide the process and give me, as the Business Intelligence professional, a platform to jump off of, so to speak. These mockups do not need to be uber-specific, but should correctly pinpoint the type of chart used, what dimensions/measures go on what axis, etc.
### 3. Create charts
To satisfy the product development team's wants, I created three dashboards, each consisting of two charts:
- Dashboard 1: A map showing the average of trip minutes + a table showing trip statistics for each neighbourhood start-end combination for the summer months, split by user type (customer vs subscriber). The dashboard also includes filters for various metrics (precipitation, temperature, windspeed, trip count), which changes the color of the map accordingly. Each neighbourhood is shaded according to how large the metric value is; darker means larger. Additionally, there are filters for neighbourhood, user type, bike ID, and month to filter the information displayed in the table.
<br>
![summer trends](Trends%20-%20Summer.png)
