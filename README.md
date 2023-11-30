Folder Description:
This repository encapsulates a comprehensive dataset comprising facial images and associated metadata, including age, ethnicity, and gender labels. The repository's structure and content aim to facilitate a nuanced understanding of the dataset, incorporating statistical analyses and preparatory steps for model training.

Statistical Insights:
The repository offers fundamental statistical insights derived from the dataset:

Age Frequency Distribution: Provides an overview of age distribution frequencies.
Age Distribution Histogram: A graphical representation of age distribution for deeper analysis.
Ethnicity Distribution Bar Chart: Illustrates the distribution of ethnicities within the dataset.
Gender Pie Chart: Presents a visual breakdown of gender distribution.
Data Preparation:
Efforts have been dedicated to ensuring data integrity and readiness for model training:

Data Cleaning (Data_cleaning): Python code specifically designed for removing corrupted images and addressing missing age values.
Model Training:
Utilizing the ResNet-50 architecture, the repository includes code for:

Age Detection Task (multi_task_ageD): Implementing the age detection task with ResNet-50.
Model Artifacts:
my_model_R50.h5: This file contains the saved trained model, ready for evaluation and potential deployment.
Visualizations:
model_loss_plot.png: An informative plot illustrating the training and validation loss throughout the model training process.
