## Adaptive Computer Vision Algorithm for Real Time Multiple On-Road Moving Vehicles Detection and Segmentation
**Project**: This project describes an adaptive learning approach to detect, and segment objects that are vehicles on road by applying computation geometry, topology and engineering physics. 

**Assumption**: Stationary camera or CCTV at traffic signals and buildings
## Solution
### Adaptive Object Detection
- Involves Gaussiam Mixture Model for frame subtraction to separate background and foreground
- Applying morphological operations and filters for pre-processing to remove noise 
- Implementing Canny Edge detection for corner and boundary of the moving object 
- Generating persistence graphs and barcodes to store object positions
### Polygon Object Instance Segmentation
- Tessilation of objects using corner points and centroid to implement polygon segmentation on moving object
- creating multiple nerve cycles on the moving objects
- Extracted features from shape descriptions using geometrical mesh on the moving objects
