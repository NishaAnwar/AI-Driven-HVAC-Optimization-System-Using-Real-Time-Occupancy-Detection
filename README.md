Project Status

🚧 This project is currently ongoing.

**Project Description:**

The project aims to optimize energy consumption in HVAC (Heating, Ventilation, and Air Conditioning) systems while ensuring thermal comfort for building occupants. The system employs a YOLO (You Only Look Once) deep learning model for real-time occupancy detection, allowing it to accurately identify the number of people in a room and their spatial distribution. To support this, robust data pipelines were developed to handle heterogeneous HVAC sensor data, including indoor temperature, humidity, airflow, and energy consumption, as well as external weather data such as temperature, humidity, and solar radiation.

By combining occupancy information with indoor and outdoor environmental data, the system implements predictive analytics to determine optimal HVAC temperature setpoints for each zone, ensuring that energy usage is minimized without compromising occupant comfort. The predictive model leverages historical and real-time data to learn patterns in occupancy behavior and environmental conditions, enabling dynamic adjustment of HVAC controls.

The project was conducted in collaboration with NASTP Delta Lahore, providing a real-world environment to test and validate the system. Results demonstrate the potential for significant energy savings, reduced HVAC operational costs, and improved thermal comfort, making the system highly applicable for smart building management.

Available Notebooks

**1. RT_DETR.ipynb**

This notebook demonstrates the core people detection pipeline. It includes:

The working implementation of the RT-DETR model

Experiments conducted to improve the accuracy of counting the number of people under different scenarios

The notebook reflects the iterative experimentation process used to evaluate and compare detection performance.

**2. HVAC_polygons.ipynb**

This notebook focuses on spatial mapping between detected regions and HVAC units. It includes:

Creation of polygons using YOLO-based detections

Mapping of these polygons to the actual HVAC units

Logical association between detected occupancy zones and corresponding HVAC systems

This mapping is a key step toward enabling occupancy-aware HVAC control.
