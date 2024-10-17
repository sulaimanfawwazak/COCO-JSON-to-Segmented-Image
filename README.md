# COCO JSON to Segmented Image Converter
This repository contains a script that converts COCO JSON annotations into visual segmented images. The COCO JSON format is widely used for storing image annotations, but it doesn't directly display the segmentation masks. This script provides an easy way to visualize those masks by converting the JSON data into segmented images.

## Features
- Converts COCO format JSON annotations into segmented images.
- Supports multiple classes with custom color mapping for each class.
- Easy to use with a simple input-output structure.
- Automatically saves segmented masks as images in the specified format (e.g., PNG).
- Visualization of segmented regions on a "black canvas."

## Dependencies
```bash
charminal==1.0.0
matplotlib==3.8.4
numpy==2.1.2
opencv_contrib_python==4.10.0.84
opencv_python==4.10.0.84
Pillow==11.0.0
skimage==0.0
tifffile==2024.7.24
```

To install all the required dependencies, you can run `pip install -r requirements.txt`