## Project Goal

The goal of this project was to create a machine-learning-ready annotated dataset for traffic scene analysis.

## Tool Used

- Roboflow

## Annotation Task

- Object detection
- Traffic scene labeling

## Classes Annotated

- Car
- Truck
- Person
- Bicycle
- Motorcycle
- Traffic sign

## Workflow

1. Uploaded traffic scene images to Roboflow.
2. Created annotation classes.
3. Annotated objects in the images.
4. Reviewed labels for consistency and missing objects.
5. Generated a dataset version.
6. Exported the dataset with train, valid, and test splits.

## Exported Dataset Structure

```text
sample_export/
├── README.dataset.txt
├── README.roboflow.txt
├── train/
├── valid/
└── test/
