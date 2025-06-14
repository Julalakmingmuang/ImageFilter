# Image Filter and Edge Detection

This project demonstrates various image processing techniques using Python libraries such as OpenCV and Matplotlib. The notebook contains examples of applying different filters and edge detection methods to an image.

## Features

- **Image Blurring**: Applies basic blur filters to smooth images.
- **Gaussian Blur**: Uses Gaussian filters to reduce noise and detail.
- **Edge Detection**:
  - Sobel filter for detecting edges in the X, Y, and XY directions.
  - Canny edge detection for identifying sharp edges in the image.

## Requirements

To run this project, make sure you have the following libraries installed:

- `opencv-python`
- `matplotlib`
- `numpy`

You can install the required packages using pip:

```bash
pip install opencv-python matplotlib numpy
```

## Usage

1. Clone this repository and navigate to the project directory.

```bash
git clone <repository-url>
cd <repository-directory>
```

2. Open the Jupyter Notebook file `ImageFilter.ipynb`.

3. Run the cells in the notebook to apply various filters and edge detection techniques to the sample image.

## Example Output

### Original vs Blurred Image
<img src="images/Original_vs_Blurred.png" alt="Original vs Blurred" width="680"/>

### Sobel Edge Detection
<img src="images/Bird_Sobel.png" alt="Sobel Edge Detection" width="1000"/>

### Canny Edge Detection
<img src="images/Bird_canny.png" alt="Canny Edge Detection" width="450"/>

### Output Grayscale Filtering
<img src="images/Bird_output.png" alt="Output Grayscale Filtering" width="450"/>

## Notes

- Ensure that the input image is placed in the correct path or update the file path in the code.
- The notebook demonstrates techniques on a sample image but can be adapted for other images by modifying the input.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- OpenCV for image processing tools.
- Matplotlib for visualization.

Feel free to contribute or raise issues if you encounter any problems!
