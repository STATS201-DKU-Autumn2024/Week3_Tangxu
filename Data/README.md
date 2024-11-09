# Predictive Maintenance Data for Vehicle Systems

This project uses two comprehensive datasets to explore predictive maintenance in vehicle systems. The **MetroPT dataset** (Veloso et al. 2022) provides a detailed archive of maintenance activities, operational metrics, and failure events from Lisbon's metro system. It is structured to support predictive maintenance modeling, offering valuable insights into operational patterns and component degradation.

Additionally, the **Turbofan Engine Degradation Simulation Data Set** (Saxena and Goebel 2008) from NASA’s Prognostics Data Repository includes time-series sensor data on turbofan engines under simulated degradation conditions. This dataset captures real-time wear patterns in high-stress components, supporting the development of models focused on early failure detection.

These datasets allow for the integration of multimodal data to enhance predictive maintenance across transportation sectors.

## References
- Saxena, A., & Goebel, K. 2008. "Turbofan Engine Degradation Simulation Data Set." NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA. https://data.nasa.gov/Aeorspace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6
- Veloso, B., Gama, J., Ribeiro, R., & Pereira, P. 2022. "MetroPT: A Benchmark Dataset for Predictive Maintenance." Zenodo. https://doi.org/10.5281/zenodo.6854240.


Here is a structured data dictionary for the datasets.
# Data Dictionary for the Predictive Maintenance Project

## MetroPT Dataset

| **Variable**       | **Description**                                                                                 | **Type**   | **Unit**              |
|--------------------|-------------------------------------------------------------------------------------------------|------------|------------------------|
| COMPONENT_ID       | Unique identifier for each component in the metro system.                                       | Integer    | -                      |
| MAINTENANCE_TYPE   | Type of maintenance activity performed (e.g., preventive, corrective).                          | String     | -                      |
| FAILURE_EVENT      | Indicates whether a failure occurred (1 = Yes, 0 = No).                                         | Integer    | -                      |
| OPERATIONAL_HOURS  | Total hours of operation for the component at the time of maintenance or failure.               | Float      | Hours                  |
| TEMPERATURE        | Recorded temperature for the component or system during operation.                              | Float      | Degrees Celsius        |
| VIBRATION_LEVEL    | Measured vibration level of the component during operation.                                     | Float      | m/s²                   |
| INSPECTION_DATE    | Date of the most recent inspection or maintenance activity.                                     | Date       | YYYY-MM-DD             |

## NASA Turbofan Engine Degradation Simulation Dataset

| **Variable**       | **Description**                                                                                 | **Type**   | **Unit**              |
|--------------------|-------------------------------------------------------------------------------------------------|------------|------------------------|
| CYCLE              | Operational cycle number, representing a single unit of operation for the engine.               | Integer    | -                      |
| FAN_SPEED          | Speed of the engine's fan, providing insight into engine performance and stress levels.         | Float      | RPM                    |
| CORE_SPEED         | Speed of the engine core, contributing to overall degradation analysis.                         | Float      | RPM                    |
| ENGINE_TEMPERATURE | Temperature inside the engine during each operational cycle, indicating stress levels.          | Float      | Degrees Celsius        |
| PRESSURE_RATIO     | Ratio of pressure across the engine's various sections, relevant for performance assessment.    | Float      | -                      |
| DEGRADATION_LABEL  | Indicates the degradation stage (1 = Initial, 2 = Moderate, 3 = Severe).                        | Integer    | -                      |

This data dictionary provides an overview of the primary variables used in the project, detailing each variable’s description, data type, and unit. This structured format facilitates consistent use and understanding of the data for predictive maintenance modeling.
