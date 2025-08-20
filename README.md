# truck_loading
The prototype optimizes truck loading in automotive logistics by processing shipment, container and truck data. Using a First-Fit Decreasing heuristic, it generates 3D visualizations of container arrangement, truck usage, and weight distribution, reducing reliance on manual planning.

In automotive manufacturing, the truck loading stage is a crucial part of outbound logistics, as it ensures that finished parts are delivered to customers efficiently and on time. Although highly important, this process is currently handled manually and depends heavily on the expertise and availability of a small number of employees.

The system’s interface enables users to upload an Excel file containing shipment details, container specifications (dimensions, stackability, and weight), and truck information (capacity and size limits). Once uploaded, the data is processed in the cloud with a single command to generate optimized loading recommendations.

The optimization method is based on the heuristic First-Fit Decreasing (FFD) approach, which prioritizes placing the largest containers first to maximize space utilization within each truck. The recommendations consider factors such as container size, weight, and stacking capacity (how many containers can be safely stacked). The output provides a 3D visualization showing the required number of trucks, the arrangement of containers within each vehicle, and the weight distribution across trucks. This prototype aims to enhance the accuracy and efficiency of shipment planning compared to the current reliance on human judgment.

The demonstration file, truck_loading.xlsx, consists of three sheets:

    Orders: contains item codes and the quantities to be shipped.

    Containers: lists each item’s dimensions, weight, and stacking characteristics.

    Trucks: defines the available vehicles’ size and maximum load capacity.

This structured input allows the system to create loading plans that reflect practical logistics constraints.
