# Edget Detection with OpenCV

This project demonstrates various image processing techniques using OpenCV. It includes models for edge detection, contour detection, and more.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/PabloMazurkiewicz/Python-Edge-Detection.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Python-Edge-Detection
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the `Codes.ipynb` file in Jupyter Notebook or any compatible IDE.
2. Run the cells to execute different models.

## Models

### Model 1 (Core)
- **Description**: Basic edge detection using the Canny filter.
- **Usage**: Displays the original and processed images using OpenCV's `imshow`.

### Model 2 (Showing Various Subplots)
- **Description**: Displays the original and edge-detected images in subplots using Matplotlib.
- **Usage**: Run the cell to see the images in a 2x2 grid.

### Model 3 (Higher Accuracy)
- **Description**: Applies Canny edge detection with higher accuracy settings.
- **Usage**: Saves and displays the edge-detected image using Matplotlib.

### Contour Detection Model
- **Description**: Detects and draws contours on the image.
- **Usage**: Displays the original, edge-detected, and contour images using OpenCV's `imshow`.

### Enhanced Version
- **Description**: Enhanced version of contour detection with additional edge detection settings.
- **Usage**: Displays the original, edge-detected, and contour images in subplots using Matplotlib.

### Accessing the Data of a Picture
- **Description**: Prints the dimensions, height, width, and number of channels of the image.
- **Usage**: Run the cell to see the image properties.

## Dependencies

All dependencies are listed in the `requirements.txt` file. Install them using:
```sh
pip install -r requirements.txt
```