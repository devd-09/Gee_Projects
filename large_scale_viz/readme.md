This project demonstrates an interactive 3D visualization of commuter movements across the San Francisco Bay Area using Pydeck in Google Colab. It integrates open commute-route data to show how residential origins connect to workplace destinations through curved arcs representing commuter intensity.

The dataset (bay_area_commute_routes.csv) contains approximately 190,000 records of home–work pairs with job counts (S000). Each arc’s thickness is proportional to S000, colored from red (home) to green (work), illustrating major flow corridors and employment hubs. The visualization focuses on the downtown region, where many dispersed origins converge into fewer, dense work zones.

The final interactive map (arc_layer_map.html) uses Pydeck’s ArcLayer on a dark basemap with 3D tilt and tooltips for exploration. It clearly reveals the spatial concentration of jobs and the structure of commuting patterns in the Bay Area.

To reproduce, open mkb_Practical_9_Large_scale_data_visualization.ipynb in Colab or Jupyter, run all cells, and view or export the resulting map.
