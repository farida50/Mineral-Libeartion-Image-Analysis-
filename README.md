# Mineral-Liberation-Image-Analysis-
This repository contains the Python-based automated image processing pipeline developed to predict mineral liberation behavior from polished section SEM images of chalcopyrite and pyrite.

## Project Overview

The project implements an automated workflow using Python to preprocess SEM images, segment mineral grains, and quantitatively analyze grain size distributions to estimate liberation efficiency. This approach supports early-stage mineral processing design by providing predictive insights from polished section textures without requiring fully liberated particle samples.

## Features

- Image preprocessing (grayscale conversion, Gaussian filtering)
- Adaptive thresholding and morphological operations
- Connected component analysis for grain detection
- Grain size distribution and liberation percentage calculation
- Batch processing support

## How to Run

1. Install required Python packages:
pip install opencv-python numpy matplotlib pandas seaborn jupyter


## Project Structure

- `data/`: SEM images and input data files
- `outputs/`: Results such as CSV files and labeled images
- `requirements.txt`: List of Python packages needed
- `LICENSE`: License information

