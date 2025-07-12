# Colon Cancer Image Analysis

This project uses image patches of colon tissue to classify whether they indicate cancerous conditions. It involves preprocessing, exploratory data analysis, model training, and evaluation using machine learning techniques.

## Project Structure

- `ML.colonCancerAnalysis.ipynb`: Main Jupyter notebook with all the analysis, model training, and results.
- `data_labels_mainData.csv`: Primary dataset with image labels used for training and validation.
- `data_labels_extraData.csv`: Additional labeled data, possibly for testing or extended training.
- `patch_images.zip/`: Directory containing the image patches (input data).
- `readme.md`: This file.
- `requirements.txt`: Contains all the modules required to run this project

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- OpenCV or PIL (for image handling)

You can install the required libraries using:

```bash
pip install -r requirements.txt
