


# Medical Imaging Registration and Segmentation

## Overview

This README file provides an overview of the joint project between the Medical Imaging Registration (MIRA) and Segmentation (MISA). The primary objective of this project is to utilize various registration techniques to generate Atlases and Tissue Models using Cerebro Spinal Fluid (CSF), White Matter (WM), and Gray Matter (GM) data. We will employ the Elastix software for the registration process, enabling 3D registration of moving images onto fixed images.

## Project Goals

1. **Image Registration**: We will use Elastix to perform both rigid and non-rigid image registration techniques to align moving images with fixed images. This step is crucial for creating accurate Atlases and Tissue Models.

2. **Generation of Atlases**: The registered images will be used to generate comprehensive Atlases that provide a reference framework for further analysis and segmentation.

3. **Tissue Models**: Utilizing the registered data, we will create detailed Tissue Models that capture the distribution and characteristics of CSF, WM, and GM within the brain.

## Software and Tools

- **Elastix**: We have chosen Elastix for its capabilities in 3D registration of medical images. Elastix supports various registration methods, transform models, similarity measures, optimization methods, interpolation methods, and multi-resolution schemes, making it a versatile tool for our project.

## Configuration Files
https://elastix.lumc.nl/modelzoo/
- For rigid registration, we will use the parameter configuration defined in the 'Par0009affine' file.
- For non-rigid registration, the parameters from the 'Par0009bspline' file will be employed.

## Getting Started

1. **Install Elastix**: If you haven't already, download and install Elastix from [the official Elastix website](http://elastix.isi.uu.nl/).

2. **Clone the Repository**: Clone this repository to your local machine, or access it from the shared project directory.


3. **Run Registration**: Use Elastix to perform the image registration, following the configuration parameters specified in 'Par0009affine' for rigid registration and 'Par0009bspline' for non-rigid registration.

4. **Generate Atlases**: After successful registration, generate Atlases from the aligned images.

5. **Create Tissue Models**: Use the registered data to create Tissue Models that represent CSF, WM, and GM within the brain.

