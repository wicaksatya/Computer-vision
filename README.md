# Circle and Cross Marker Detection with OpenCV
This repository implements algorithms for detecting circle and cross markers in images using OpenCV.

## Techniques Used
Canny Edge Detection: This algorithm identifies strong edges within the image, useful for finding the boundaries of the markers.
Hough Transform (Circle): This technique identifies circles in the image based on the edge points detected by Canny edge detection.
Template Matching (Cross): A pre-defined template image of the cross marker is used to locate its position within the main image.

## Getting Started
Clone this repository:
`git clone https://github.com/wicaksatya/sensor-chip-detection.git`

## Usage
1. Circle Marker Detection:
  - Run the circle_detection.py script.
  - Provide an input image containing circular markers.
  - The script will apply the Hough transform and display the detected circles.
2. Cross Marker Detection:
  - Run the cross_detection.py script.
  - Input an image with cross-shaped markers.
  - The script will perform template matching to locate the crosses.

Expected Output
1. The script will display the original image with detected circles and bounding boxes around identified cross markers.
2. The center point of circle and cross marker will also be displayed.

## Additional Notes
- This is a basic implementation and might require adjustments depending on the complexity of your markers and image conditions.
- You can modify the script to include functionalities like filtering detected circles based on size or refining cross marker template matching for better accuracy.

## Further Exploration
- Explore different parameters for Canny edge detection and Hough transform to optimize circle detection for your specific use case.
- Consider using machine learning techniques for more robust cross marker detection, especially if the marker design has variations.
