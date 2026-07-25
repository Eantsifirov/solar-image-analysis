# Solar Image Analysis

A Python-based scientific computing project for preprocessing and analyzing solar observations stored in FITS format.

The project includes image preprocessing, automated sunspot detection, heliographic coordinate calculations, and differential rotation analysis based on observational data.

## Features

* Loading and processing solar FITS images
* Image rotation and preprocessing
* Automated detection of sunspot regions
* Calculation of sunspot coordinates
* Analysis of solar differential rotation
* Scientific visualization of observational results

## Technologies

* Python
* NumPy
* SciPy
* Astropy
* Matplotlib
* Jupyter Notebook

## Repository Structure

```text
.
├── data/
│   └── README.md
├── src/
│   └── solar_image_analysis.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Eantsifirov/solar-image-analysis.git
cd solar-image-analysis
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook src/solar_image_analysis.ipynb
```

The observational FITS datasets are not included in the repository because of their size. See [`data/README.md`](data/README.md) for additional information.

Before running the notebook, update the dataset paths to point to the FITS files stored on your computer.

## Project Status

This repository contains the results of a technical internship project in scientific image processing.

The current version is provided as a Jupyter Notebook. The preprocessing and sunspot-analysis components may be separated into reusable Python modules in a future revision.

## License

This project is licensed under the MIT License.


## License

This project is licensed under the MIT License.
