# face_swapping
- About
  
In this project, we aim to develop a system that performs face detection and swapping between two images. The application allows users to upload two images, automatically detects faces within these images, and provides the functionality to swap faces between them.

- Libraries
    
    In this project we are using these libraries :-
    
    - `tkinter` and its components for creating and managing the GUI.
    - `PIL` (Python Imaging Library) components for image operations.
    - `cv2` from OpenCV for image processing, including face detection.
    - `numpy` for handling image data as arrays.

- Libraries Installation
    
    To install the libraries required for this project involving `tkinter`, `PIL`, `cv2`, and `numpy`, follow the instructions below for different operating systems.
    
    ### Instructions for Installing Required Libraries
    
    ### 1. Installing `tkinter`
    
    `tkinter` is typically included with Python on most systems, but you might need to install it manually depending on your OS.
    
    - **Windows**:
    `tkinter` comes bundled with the Python installer. Ensure that you have installed the standard Python distribution from [python.org](https://www.python.org/).
    - **Mac**:
    `tkinter` is included with the Python framework installed from [python.org](https://www.python.org/). However, if you encounter issues, you may need to install it separately:
        
        ```bash
        bashCopy code
        brew install python-tk
        
        ```
        
    - **Linux (Debian/Ubuntu)**:
    Use the following command to install `tkinter`:
        
        ```bash
        bashCopy code
        sudo apt-get install python3-tk
        
        ```
        
    - **Linux (Fedora)**:
    Use the following command to install `tkinter`:
        
        ```bash
        bashCopy code
        sudo dnf install python3-tkinter
        
        ```
        
    
    You can verify if `tkinter` is installed by running a simple test in the Python interpreter:
    
    ```python
    pythonCopy code
    import tkinter
    print(tkinter.TkVersion)
    
    ```
    
    ### 2. Installing `PIL` (Pillow)
    
    `PIL` has been replaced by `Pillow`, which is a more updated and user-friendly version of the library. Install it using `pip`:
    
    ```bash
    bashCopy code
    pip install pillow
    
    ```
    
    ### 3. Installing `cv2` (OpenCV)
    
    `cv2` is the Python interface for OpenCV, and it can be installed via `pip`:
    
    ```bash
    bashCopy code
    pip install opencv-python
    
    ```
    
    For additional functionalities, you might also want to install `opencv-python-headless` (if you're running in an environment without GUI support, like a server):
    
    ```bash
    bashCopy code
    pip install opencv-python-headless
    
    ```
    
    ### 4. Installing `numpy`
    
    `numpy` is a powerful library for numerical computations and handling arrays. It can be installed using `pip`:
    
    ```bash
    bashCopy code
    pip install numpy
    
    ```
    
    ### Installing All Libraries at Once
    
    You can also install all the required libraries in one go by listing them in a `requirements.txt` file and using `pip` to install from that file. Create a file named `requirements.txt` with the following content:
    
    ```
    txtCopy code
    pillow
    opencv-python
    numpy
    
    ```
    
    Then run:
    
    ```bash
    bashCopy code
    pip install -r requirements.txt
    
    ```
    
    ### Verifying the Installation
    
    After installing, you can verify that the libraries are correctly installed by running a Python script or directly testing in the Python interpreter:
    
    ```python
    pythonCopy code
    import tkinter as tk
    from PIL import Image, ImageTk
    import cv2
    import numpy as np
    
    # If no errors are raised, the installations were successful
    print("All libraries are installed and imported successfully.")
    
    ```
    
    ### Troubleshooting
    
    If you encounter any issues during the installation:
    
    - Ensure that you have `pip` and Python installed correctly. You can check the version by running `python --version` and `pip --version`.
    - Make sure your `pip` is up to date with `pip install --upgrade pip`.
    - For `tkinter`, make sure that the corresponding `tk` packages are installed on your system if it's not bundled with your Python installation.
