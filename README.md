
# ABOUT OUR PROJECT

# Digital-Twin-of-Ship-Hull-Corrosion


The Digital Twin of a Ship Hull for Illustrating Biofouling Dynamics project aims to develop a predictive maintenance system for ships, reducing downtime at ports for maintenance.
This system is part of a larger initiative to use underwater drones to capture images, interpolate them on a ship model, and mitigate biofouling.

Model Importation: The ship hull model was imported using the GLTF loader.
The model was made permanent to avoid importing different models each time.

Mesh Hierarchy: A 'Mesh Hierarchy' button was added to display the hierarchy of the model's mesh components.

Light and Scene Properties: Implemented functionality to alter light type and intensity.
Added an option to view the wireframe of the entire model.

Mesh Properties: Upon clicking a particular component of the model, the 'Mesh Properties' button gets activated. Users can change the color of the selected component and view its wireframe.
Detailed information about the component, such as the number of edges, vertices, and triangles, is displayed.

Progressive Corrosion Display: Introduced a button to show progressive corrosion.
When clicked, this feature updates images on the hull every 10 seconds to illustrate progressive corrosion. Logs of the date, time, and name of each image are displayed.

Hotspots: Added hotspots to the model.
Clicking on a hotspot displays its description along with values of resistance and corrosion.

These values are read from a CSV file using APIs.
