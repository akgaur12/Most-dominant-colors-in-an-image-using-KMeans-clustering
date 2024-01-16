# Most Dominant Colors in an Image Using KMeans Clustering

## Overview
This repository contains a Python script that utilizes KMeans clustering to identify the most dominant colors in an image. By employing the popular scikit-learn library, the script provides a simple and efficient way to extract key color information from images.

## How it Works
The script takes an image as input and applies the KMeans clustering algorithm to group pixels with similar colors. The centroids of these clusters represent the dominant colors in the image. The user can specify the number of dominant colors to extract.

## Dependencies
- Python 3.x
- NumPy
- OpenCV
- scikit-learn

Install the required dependencies using the following command:
```bash
pip install numpy opencv-python scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Most-Dominant-Colors.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Most-Dominant-Colors
   ```

3. Run the script with the desired image and number of dominant colors:
   ```bash
   python dominant_colors.py --image your_image.jpg --k 3
   ```

   Adjust the `--k` parameter to specify the number of dominant colors to extract.

## Example
```bash
python dominant_colors.py --image sample_image.jpg --k 5
```

This command will process the `sample_image.jpg` and display the top 5 dominant colors.

Feel free to explore and modify the script to suit your specific needs.

Happy coding! 🚀
