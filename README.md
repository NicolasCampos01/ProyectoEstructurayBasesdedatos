# ProyectoEstructurayBasesdedatos
# Solar Image Analysis Project

## **Overview**
This project focuses on developing a flexible and robust system for managing and analyzing solar observation data using **MongoDB** and **FITS files**. The primary objective is to enable efficient storage, querying, and visualization of structured and unstructured astronomical data. By integrating tools like **Astropy**, the system provides advanced capabilities for processing and analyzing solar images and metadata.

---

## **Features**
- **Data Storage**: 
  - Uses **MongoDB** with GridFS to store large FITS files and their metadata.
- **Data Querying**:
  - Supports advanced queries to filter images by wavelength, date range, and other metadata.
  - Implements aggregation pipelines for statistical analysis.
- **Data Analysis**:
  - Extracts and analyzes key parameters such as CCD temperature, solar radius, and wavelengths.
  - Provides functionality to filter and visualize these parameters.
- **Visualization**:
  - Generates dynamic plots for metadata parameters.
  - Displays solar images directly from FITS files.

---

## **Technologies Used**
- **MongoDB**:
  - Database for managing and querying metadata.
  - GridFS for storing large FITS files.
- **Astropy**:
  - For handling and processing FITS files.
- **Matplotlib**:
  - For generating plots and visualizations.
- **Python**:
  - Core language for data processing and system implementation.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/solar-image-analysis.git
   cd solar-image-analysis
