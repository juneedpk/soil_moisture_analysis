# Soil Moisture Analysis in Pakistan

## Overview
This project analyzes soil moisture data in Pakistan using the TERRA CLIMATE dataset from 2013 to 2023. The analysis aims to compute monthly mean soil moisture, investigate correlations with precipitation and potential evapotranspiration (PET), and generate zonal statistics to provide insights into water availability and its implications for agriculture and environmental management.

## Table of Contents
- [Getting Started](#getting-started)
- [Data](https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE)
- [Analysis](#analysis)
- [Visualization](#visualization)
- [Exporting Results](https://littledew31.users.earthengine.app/view/soil-moisture-analysis-of-pakistan-2013-2023)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Getting Started
To run this project, you will need to use Google Earth Engine (GEE). Follow the steps below to get started:

1. **Sign Up for Google Earth Engine**: If you don't have an account, sign up at [Google Earth Engine](https://earthengine.google.com/).
2. **Open the Code Editor**: Go to the [GEE Code Editor](https://code.earthengine.google.com/) to create a new script.
3. **Copy the Code**: Copy the provided code into the GEE Code Editor.

## Data
The project uses the following dataset:
- **TERRA CLIMATE**: An image collection that provides high-resolution climate data, including soil moisture, precipitation, and potential evapotranspiration.

## Analysis
The analysis involves the following key steps:
1. Load the TERRA CLIMATE dataset.
2. Define the geographical boundaries of Pakistan.
3. Filter the dataset for soil moisture from 2006 to 2010.
4. Compute monthly mean soil moisture.
5. Analyze correlations with precipitation and PET.
6. Generate zonal statistics for soil moisture.

## Visualization
The monthly mean soil moisture is visualized using a color palette to represent different moisture levels. A legend is included to enhance interpretation.

## Exporting Results
Results are exported as:
- **GeoTIFF**: High-resolution images of monthly mean soil moisture.
- **CSV**: Zonal statistics for further analysis.
## Project Link
[Soil Moisture Analysis of Pakistan](https://littledew31.users.earthengine.app/view/soil-moisture-analysis-of-pakistan-2013-2023)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Google Earth Engine](https://earthengine.google.com/) for providing the dataset and analysis tools.
- TERRA CLIMATE team for their valuable climate data.
- Junaid Amin ( Environmentalist & Data Scientist)

---

Feel free to modify or add any sections to better suit your project needs!
