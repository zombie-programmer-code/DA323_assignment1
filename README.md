# DA323_assignment1

This repository contains several parts of the DA323 assignment, including TASK1 and TASK3. Each subpart is uploaded as a separate file.

---

## Project Overview

The project is divided into multiple datasets and tasks:

- **Images**: Stored in 20 folders, each representing a distinct category.
- **Weather Data**: Weather records for February 2025 from 20 Indian cities.
- **Scraped Articles**: Text data for 20 categories.
- **Radio Recordings**: Audio clips used for country prediction.
- **National Anthems & Flags**: 
  - Flags in PNG format.
  - English translations of national anthems.
  - Audio recordings of the national anthems.
- **Country Mapping**: A JSON file mapping country codes to country names.
- **Additional Data**: A CSV file used for exploratory data analysis (EDA) in one of the tasks.

---

## Folder Structure & Data Files

- **Images (20 Categories)**  
  The following folders contain images for each category:
  1. **airplane**
  2. **bicycle**
  3. **book**
  4. **car**
  5. **cat**
  6. **chair**
  7. **chess board**
  8. **computer**
  9. **dog**
  10. **food**
  11. **headphones**
  12. **mountains**
  13. **shirt**
  14. **shoe**
  15. **sunset**
  16. **table**
  17. **tie**
  18. **watch**
  19. **zoo**
  20. **skyscraper**

- **Image Metadata**:  
  `image_metadata.csv` contains details about the images.

- **Weather Data**:  
  Located in the `weather_data_last_30_days` folder.

- **Scraped Articles**:  
  Available in the `scraped_articles` folder.

- **Radio Recordings**:  
  Found in the `radio_recording` folder.

- **National Anthems & Flags**:
  - **Flags**: In the `png_flags` folder (extracted from [nationalanthems.info](https://nationalanthems.info/)).
  - **Anthems (Translations)**: In the `national_anthems` folder.
  - **Anthems (Audio)**: In the `national_anthems_audio` folder.

- **Country Mapping**:  
  `countries.json` provides a mapping from country codes to country names.

- **Additional Dataset**:  
  `da323_assignment1_task1_e.csv` is used in TASK1 Part E, sourced from [data.gov.in](https://www.data.gov.in/).

---

## Notebooks & Their Purposes

- **DA323-TASK1-partA-220150019.ipynb**  
  *Trains an image classifier using the images folder.*

- **DA323_assignment1_TASK1_partB.ipynb**  
  *Trains an LSTM text classifier using the scraped articles.*

- **DA323-TASK1-partC-220150019.ipynb**  
  *Trains a classifier to predict the country of origin from radio recordings.*

- **DA323-TASK1-partD-220150019.ipynb**  
  *Trains an LSTM model to predict the temperature for the next hour, using the previous 48 hours of weather data.*

- **DA323_assignment1_TASK1_partE.ipynb**  
  *Performs exploratory data analysis (EDA) on the dataset in `da323_assignment1_task1_e.csv`.*

- **DA323_assignment-TASK3.ipynb**  
  *Analyzes data from `png_flags`, `national_anthems`, and `national_anthems_audio` for both unimodal and multimodal analyses.*

---

## How to Use

1. **Clone the Repository**:  
   `git clone <repository-url>`

2. **Explore the Folders**:  
   Familiarize yourself with the data folders and files. You may have to change the paths of the folders to your own local paths

3. **Run the Notebooks**:  
   Open the relevant Jupyter Notebook (.ipynb) in your preferred environment (e.g., JupyterLab, VSCode) and follow the instructions provided within each notebook.

---

Feel free to explore each section of the repository
