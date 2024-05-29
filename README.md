# Cell Recognition and Segmentation with Stardist


## Overview
This program uses the Stardist library to perform cell recognition and segmentation on input images. It processes both 2D and 3D images, applies segmentation, and generates an automatic report with visualizations of the segmented images.

## Features

Cell recognition and segmentation using Stardist.
Supports both 2D and 3D images.
Normalizes input images for better segmentation results.
Generates visualizations of original and segmented images.
Automatically creates a report with the segmented results.

## Installation
Clone the repository:

```
git clone https://github.com/mariacastillo982/Cell-recognition.git
cd Cell-recognition
```

Create a virtual environment and activate it:

```
conda create -n cell_recognition 
conda activate cell_recognition
```

Install the required packages:

```
!pip install stardist
!pip install csbdeep
!pip install tifffile
!pip install imagecodecs
```

## Usage

* Prepare Input Images:

Define the path where the input images are located at the variable `image_folder` defined at the main jupyter notebook `cell_recognition_ntb.ipynb`

* Run the Segmentation:

The segmented images and the generated report will be saved in the `output_images` folder.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or features.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or issues, please contact `mary_gomez982@hotmail.com`


