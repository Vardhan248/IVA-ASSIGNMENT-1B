# IVA-ASSIGNMENT-1B

1. Color Detection (color_detection(image_path))
Detects red color in an image using HSV color space.
Applies a mask to extract red regions.
Useful for detecting specific colors in an image.
2. Image Pyramid (compute_t_pyramid(image_path))
Generates a Gaussian Pyramid by repeatedly reducing image size.
Helps in multi-scale processing, object detection, and image compression.
3. Image Smoothing (image_smoothing(image_path))
Uses Gaussian Blur to remove noise and smooth the image.
Helps in improving image quality before applying further processing like edge detection.
4. Edge Detection (edge_detection(image_path))
Identifies edges in an image using:
Sobel X: Detects vertical edges.
Sobel Y: Detects horizontal edges.
Canny Edge Detection: Finds sharp edges efficiently.
Used in feature extraction and object recognition.
5. Object Detection (object_detection(image_path))
Uses Haar Cascade Classifier to detect faces in an image.
Converts the image to grayscale for faster processing.
Draws bounding boxes around detected faces.


Steps to execute:
- load the Images - first, second, third, four, five
- run the program
- Check the output
