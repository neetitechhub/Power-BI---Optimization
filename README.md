# Power-BI-Optimization

**Power BI Performance Optimization Technique :**

1. Use Proper Data Types to optimize storage and calculations.
2. Minimize unique values in columns where possible to speed up processing.
3. Only load the data you need for your reports.
4. Design your data model using a star schema with fact and dimension tables.
5. Apply filters in your queries to import only relevant data.
6. Write efficient DAX formulas and avoid complex calculations on the fly.
7. Pre-aggregate data in your source or in Power BI to reduce the volume of data.
8. Limit the number of visuals on each report page to reduce rendering time.
9. Use visuals that are less resource-intensive, such as bar charts over more complex visuals like maps.
10. Avoid overlapping visuals and excessive use of custom visuals.
11. Utilize Power BI's Performance Analyzer tool to identify and troubleshoot performance bottlenecks.
12. Regularly check the performance of your reports and make adjustments as needed.
13. Use incremental refresh to update only the new or changed data instead of the entire dataset.
14. Ensure your data source is optimized for querying and can handle the load.
15. Optimize queries using techniques such as query folding, which pushes operations back to the data source.
16. Schedule data refreshes during off-peak hours to avoid performance degradation during business hours.
17. Minimize the use of visuals that require complex calculations or large datasets.
18. Use bookmarks and report navigation to optimize user experience and reduce unnecessary data loading.
19. Avoid overusing slicers and filters that may slow down interactivity.
