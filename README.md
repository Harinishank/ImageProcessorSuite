# Image Processing Algorithms
This project implements several fundamental image processing techniques using various algorithms. The operations included are:

1. **Grayscale Conversion:** Color space transformation.
2. **Gaussian Blur:** Convolution with a Gaussian kernel.
3. **Rotation:** Affine transformation.
4. **Cropping:** Array slicing.
5. **Negative Image:** Bitwise NOT operation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Algorithms](#algorithms)
  - [Grayscale Conversion](#grayscale-conversion)
  - [Gaussian Blur](#gaussian-blur)
  - [Rotation](#rotation)
  - [Cropping](#cropping)
  - [Negative Image](#negative-image)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harinishank/image-processing-algorithms.git
    cd image-processing-algorithms
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the image processing functions, import the `image_processing` module and call the desired function with the appropriate parameters.

```python
from image_processing import grayscale_conversion, gaussian_blur, rotate_image, crop_image, negative_image

# Example usage
gray_image = grayscale_conversion(input_image)
blurred_image = gaussian_blur(input_image, kernel_size=5)
rotated_image = rotate_image(input_image, angle=45)
cropped_image = crop_image(input_image, x_start=50, y_start=50, width=100, height=100)
negative = negative_image(input_image)
```

## Algorithms

### Grayscale Conversion

**Color space transformation** converts a color image to grayscale by calculating the weighted sum of the color channels.

```python
def grayscale_conversion(image):
    # Implementation here
    pass
```

### Gaussian Blur

**Convolution with a Gaussian kernel** smooths the image by averaging the pixel values with their neighbors, weighted by a Gaussian function.

```python
def gaussian_blur(image, kernel_size):
    # Implementation here
    pass
```

### Rotation

**Affine transformation** rotates the image around its center by a specified angle.

```python
def rotate_image(image, angle):
    # Implementation here
    pass
```

### Cropping

**Array slicing** extracts a rectangular region from the image.

```python
def crop_image(image, x_start, y_start, width, height):
    # Implementation here
    pass
```

### Negative Image

**Bitwise NOT operation** inverts the colors of the image, creating a negative effect.

```python
def negative_image(image):
    # Implementation here
    pass
