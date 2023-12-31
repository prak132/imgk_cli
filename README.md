# Imgk
* Imgk is a simple image processing utility that provides various functionalities for manipulating and processing images from the command line.
* This is my first time making a cli prodject and this is very basic, this is just wrapping the pillow library for use in the command line.

# Features
* Image resizing: Resize images to specific dimensions.
* Image conversion: Convert images to different formats.
* Image cropping: Crop images to a specified region.
* Image filtering: Apply various filters and effects to images.
* Image metadata extraction: Extract metadata information from images.

# Installation
You can install imgk using PyPI:

```bash
pip install imgk
```

**Make sure you have Python 3.9 or later installed.**

If not go to this [website](https://www.python.org/downloads/) and download python 3.9

# Usage

To use imgk, open a terminal and run the `imgk` command followed by the desired subcommand and options.

Examples:
* Resize an image:
```bash
imgk resize --width 800 --height 600 input.jpg output.jpg
```
* Convert an image:
```bash
imgk convert --format png input.jpg output.png
```
* Crop an image:
```bash
imgk crop --x 100 --y 100 --width 200 --height 200 input.jpg output.jpg
```
* Apply a filter to an image:
```bash
imgk filter --type grayscale input.jpg output.jpg
```
* Extract metadata from an image:
```bash
imgk metadata input.jpg
```
**For more information and available options, run imgk --help**

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contributing
Feel free to submit issues and pull requests.

# Acknowledgements
* [Pillow](https://python-pillow.org/) - Python Imaging Library (PIL)

# Author
Prakhar Rathore - [GitHub](https://github.com/prak132)
