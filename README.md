# EcoBite

EcoBite is a project focused on classifying and managing waste through AI-driven models. This repository contains resources and code for training and applying AI models specifically designed for Food Waste and General Waste classification. Each main category includes Jupyter notebooks for both training and model application.

## Project Structure

The repository is organized into two primary folders:

### 1. FoodWasteClassifier
- Contains AI model resources and scripts focused on classifying various types of food waste.

- Notebooks:
  - Training Notebook: For training the Food Waste classification model.
  - Application Notebook: Uses the trained model to classify food waste in real-time. (Note: This notebook may open a camera feed for live classification.)
 
### 2. GeneralWaste
- Contains AI model resources and scripts for classifying general waste types (e.g., plastics, metals, paper).
- Notebooks:
  - Training Notebook: For training the General Waste classification model.
  - Application Notebook: Uses the trained model to classify general waste in real-time. (Note: This notebook may open a camera feed for live classification.)

### Running the Notebooks

Set up dependencies: Ensure you have all required libraries installed, especially opencv, pandas, torch, and ultralytics.
Run Jupyter Notebooks: Open each folder and run the corresponding notebooks as needed.
Training Notebooks: Train the models using labeled datasets. Customize parameters within the notebook if necessary.
Application Notebooks: Test the trained models with real-time camera feed for classification (camera access required).
Output: Results will display annotated frames in the application notebook and provide live detection outputs.
