# Most Dominant Colors in an Image Using KMeans Clustering

## Overview
This repository contains a Python script that utilizes KMeans clustering to identify the most dominant colors in an image. By employing the popular scikit-learn library, the script provides a simple and efficient way to extract key color information from images.

## How it Works
The script takes an image as input and applies the KMeans clustering algorithm to group pixels with similar colors. The centroids of these clusters represent the dominant colors in the image. The user can specify the number of dominant colors to extract.

## Features
- Utilizes the KMeans clustering algorithm for color segmentation.
- Extracts and visualizes the most dominant colors in the input image.
- Offers flexibility to adjust the number of dominant colors to be identified.
  
## Dependencies
- Python 3.x
- NumPy
- OpenCV
- scikit-learn

Install the required dependencies using the following command:
```bash
pip install numpy opencv-python scikit-learn
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or suggest improvements. Happy coding! 🚀
