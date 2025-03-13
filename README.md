# ML_Workshop

This repository was created for workshop purposes. It contains machine learning code in two formats to accommodate different working environments.

## Repository Structure

- **WorkshopML_Colab**: Code prepared to run on Google Colab.
- **WorkshopML_Local**: Code intended to run on your local computer.

## Running on Google Colab

### Requirements
- A Google account
- Internet connection
- Google Drive

### Setup Instructions
1. Download the repository as a ZIP file from GitHub
2. Extract the ZIP file on your computer
3. Upload the extracted folder to your Google Drive
4. Navigate to the folder in Google Drive
5. Open the `WorkshopML_Colab/Workshop_Colab.ipynb` notebook by right-clicking and selecting "Open with Google Colaboratory"

Google Colab provides a ready-to-use environment with most of the required libraries pre-installed, so you can immediately start running the notebook cells.

## Running Locally

### Requirements
- Python 3.9 or higher
- Jupyter Notebook
- Conda or Miniconda (for environment setup)

### Setup Instructions

1. Download the repository as a ZIP file from GitHub and extract it on your computer:
   ```
   cd ML_Workshop
   ```

2. Create and activate the conda environment using the provided `environment.yml` file:
   ```
   conda env create -f WorkshopML_Local/environment.yml
   conda activate ML_Workshop
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Navigate to `WorkshopML_Local/Workshop_Local.ipynb` and open it

5. Ensure you're using the correct kernel:
   - In the Jupyter Notebook menu, go to **Kernel** > **Change kernel**
   - Select the `ML_Workshop` kernel (which was created from the environment.yml file)

### Environment Details

The `environment.yml` file includes all necessary libraries:
- Python 3.9
- pandas
- numpy
- joblib
- matplotlib
- seaborn
- scikit-learn
- xgboost
- tensorflow
- hvplot
- holoviews
- panel
- jupyter_bokeh
- tensorflow

## Input and Output Directories

- Both versions of the workshop code use the `inputs` directory for data sources
- Results will be saved to the `outputs` directory

## Support

If you encounter any issues or have questions, please contact:
- Kevin He (kevin.he@water.ca.gov) 
- Peyman Namadi (peyman.hosseinzadehnamadi@water.ca.gov)
- Or open an issue in this repository
