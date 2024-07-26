# Power-BI-Optimization

**Power BI Performance Optimization Technique :**

.Use Proper Data Types to optimize storage and calculations.
.Minimize unique values in columns where possible to speed up processing.
.Only load the data you need for your reports.
.Design your data model using a star schema with fact and dimension tables.
.Apply filters in your queries to import only relevant data.
.Write efficient DAX formulas and avoid complex calculations on the fly.
.Pre-aggregate data in your source or in Power BI to reduce the volume of data.
.Limit the number of visuals on each report page to reduce rendering time.
.Use visuals that are less resource-intensive, such as bar charts over more complex visuals like maps.
.Avoid overlapping visuals and excessive use of custom visuals.
.Utilize Power BI's Performance Analyzer tool to identify and troubleshoot performance bottlenecks.
.Regularly check the performance of your reports and make adjustments as needed.
.Use incremental refresh to update only the new or changed data instead of the entire dataset.
.Ensure your data source is optimized for querying and can handle the load.
.Optimize queries using techniques such as query folding, which pushes operations back to the data source.
.Schedule data refreshes during off-peak hours to avoid performance degradation during business hours.
.Minimize the use of visuals that require complex calculations or large datasets.
.Use bookmarks and report navigation to optimize user experience and reduce unnecessary data loading.
.Avoid overusing slicers and filters that may slow down interactivity.
