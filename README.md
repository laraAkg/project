## Project Overview

**[Include a brief description of what your project does and its purpose. Highlight its main features or functionalities.]**

## Installation

**[Provide detailed steps on how to install your project. Include any prerequisites, dependencies, or setup instructions.]**

## Usage

### country_code_data_utils.ipynb

The **`country_code_data_utils.ipynb`** notebook is a crucial component responsible for fetching, processing, and storing country code data retrieved from the XY API. This API supplies a list of countries, each identified by a unique code (e.g., 'CH' for Switzerland), which we store in our database for future reference.

#### Instructions:

1. **Order of Execution**: Run each cell in sequential order to avoid any dependency issues.

2. **Data Update Process**: If there are new versions of the data available, follow these steps:
   - Uncomment the 'drop table' code to delete the existing table.
   - Run the cells to execute the deletion.
   - Comment the 'drop table' code again to prevent accidental deletion in the future.

3. **Fetching and Processing Data**: Once the 'drop table' code is commented again, run all cells to fetch and process the new data. Ensure all cells execute successfully.

#### Notes:
- The data processed within this notebook is utilized in other sections of the application, making its accurate processing crucial.
- Regularly check for updates from the XY API to ensure the database remains current.
