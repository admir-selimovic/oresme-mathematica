# Oresme [Wolfram Mathematica]: 3D Shape Feature Engineering for Machine Learning

![3D Computer Graphics](https://img.shields.io/badge/3D%20Computer%20Graphics-007ACC) 
![Computational Geometry](https://img.shields.io/badge/Computational%20Geometry-FF6347)
![Geometry Processing](https://img.shields.io/badge/Geometry%20Processing-007ACC) 
![Feature Engineering](https://img.shields.io/badge/Feature%20Engineering-FF4500)

![Wolfram Mathematica](https://img.shields.io/badge/Wolfram%20Mathematica-DD1100?style=flat&logo=wolfram-mathematica)


<div align="center"> 
  <img src="https://github.com/admir-selimovic/oresme-mathematica/blob/main/img/glypta-2.png" width="300">
</div>

# Oresme

Oresme is a Wolfram Mathematica implementation dedicated to advanced data processing and point cloud generation from 3D objects. It is primarily designed to perform feature engineering on 3D shapes, making them ready for machine learning applications.

## Description

Oresme is designed to analyze defects in datasets, preprocess 3D models, generate point clouds, and perform various mathematical and geometric operations, ensuring that the data are primed for machine learning. on the data. With sophisticated algorithms, the project offers an all-in-one solution to manipulate and extract meaningful information on the shape of 3D models.

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
2. Open the Mathematica notebook `oresme.nb`.
3. Run the entire notebook or individual cells as needed.
4. Monitor the progress dynamically within the notebook.

## Notes

- Some functions assume the availability of specific datasets and variables. Ensure you have the necessary data before running these functions.
- Make sure the directory from which the project is run contains the required `.obj` files and associated texture files for proper execution.

## Contribution

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Licensing

This project is licensed under the MIT license.

