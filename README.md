# Glypta

Glypta is a Mathematica-based project dedicated to advanced data processing and point cloud generation from 3D objects.

## Description

The Glypta project is designed to analyze defects in datasets, preprocess 3D models, generate point clouds, and perform various mathematical and geometric operations on the data. With sophisticated algorithms, the project offers an all-in-one solution to manipulate and extract meaningful information from 3D models.

## Features

- **3D Model Preprocessing**: Handles the import of `.obj` files, computes the model data, and fixes any mesh defects. Additionally, it adjusts the mesh coordinates and extracts critical details about the 3D mesh.

- **Point Cloud Generation**: Dynamically creates a point cloud representation of the 3D model with progress indicators.

- **Defect Analysis**: Evaluates the point cloud data to identify and address defects.

- **Principal Curvature Analysis**: Calculates and visualizes the principal curvature of the 3D models.

- **Dynamic Status Updates**: Throughout the processing, it provides dynamic updates on the Mathematica frontend about the progress and current status of each step.

## Dependencies

Ensure you have the latest version of Mathematica installed. This project relies on certain built-in Mathematica functions and capabilities, which may not be present in older versions.

## Usage

1. Clone the repository to your local machine.
2. Open the Mathematica notebook `glypta.nb`.
3. Run the entire notebook or individual cells as needed.
4. Monitor the progress dynamically within the notebook.

## Notes

- Some functions assume the availability of specific datasets and variables. Ensure you have the necessary data before running these functions.
- Make sure the directory from which the project is run contains the required `.obj` files and associated texture files for proper execution.

## Contribution

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Licensing

This project is licensed under the MIT license.

