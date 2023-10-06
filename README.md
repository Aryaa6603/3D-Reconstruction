# 3D Reconstruction from 2D input using NVDiffrec
Description
This project is a 3D reconstruction tool based on nvdiffrec. It aims to provide a convenient way to perform 3D reconstruction using various dependencies and libraries.
Installation
To install and use this project, please follow the steps below:

1. Make sure you have Python 3.9.0 or a later version installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.

Dependencies
This project relies on the following dependencies:

- glfw (version 2.5.3): A library for creating windows with OpenGL contexts.
- gdown (version 4.4.0): A tool for downloading files from Google Drive.
- xatlas (version 0.0.6): A library for creating texture atlases.
- click (version 8.0.3): A command-line interface toolkit.
- rembg (version 2.0.21): A library for removing backgrounds from images. This version includes GPU support.
- Pillow (version 9.0.1): A Python Imaging Library.
- imageio (version 2.19.3): A library for reading and writing image data.
- pre-commit (version 2.19.0): A framework for managing and maintaining multi-language pre-commit hooks.
- scikit-image (version 0.19.1): A collection of algorithms for image processing.
- opencv-python (version 4.6.0): A library for computer vision and image processing.
- dvc (version specified as ""): A version control system for machine learning projects. This version includes Google Storage support.

Installation
To run the notebook and associated Python files on your local system, please follow the steps below:

1. Make sure you have Python 3.7 or a later version installed on your system.

2. Clone this repository to your local machine or download the ZIP file and extract it.

3. Open a terminal or command prompt and navigate to the project directory.

4. Install the required dependencies by running the following command:
      pip install -r requirements.txt

Usage
To use the annotation tool and run the Python files, please follow the instructions provided in the vid_keyframe_annotation.ipynb notebook. The notebook contains code cells that can be executed by clicking on them and pressing Shift + Enter. Make sure to run the code cells in the correct order to ensure proper execution.

The notebook provides a step-by-step guide on how to use the annotation tool, modify the frame processing function, perform post-processing steps, and generate the desired output files.
Additional Python Files
In addition to the Jupyter Notebook, there are several Python files included in this project. These files are referenced and used within the notebook. You can run these Python files separately if needed, but it is recommended to follow the instructions and run the code within the notebook for a complete workflow.
 
## Development Dependencies
The following dependencies are required for development purposes:

- flake8 (version 4.0.1): A tool for enforcing coding style and checking for potential errors.
- black (version 22.3.0): A code formatter for Python.
