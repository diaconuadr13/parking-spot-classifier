# Parking Spot Classifier

This project uses a Convolutional Neural Network (CNN) to classify whether a parking spot is occupied or not.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have the following packages installed:

- PyTorch
- OpenCV
- PIL

You can install them using pip:

```bash
pip install torch opencv-python pillow
```
## Dataset

This project uses the XYZ dataset, which is not included in this repository due to its size. You can download the dataset from [this link](https://github.com/fabiocarrara/deep-parking/releases/download/archive/CNRPark-Patches-150x150.zip).

After downloading, unzip the dataset and place it in a directory named `data` in the root of this project. Merge all the "busy" and "free" folders so that inside your data folder you only have two subfolders: "busy" and "free".

