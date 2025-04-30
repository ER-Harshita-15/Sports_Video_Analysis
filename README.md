# Basketball Video Analysis

This project provides tools and techniques for analyzing basketball videos, including color detection, court detection, homography mapping, and Mask R-CNN-based object detection.

## Project Structure

basketballVideoAnalysis/ ├── color-detection/ │ ├── plot_csv.py │ ├── show_colors.py │ ├── team_color.csv │ ├── images/ │ └── README.md ├── court-detection/ │ ├── court_detection1.py │ ├── input/ │ ├── output/ │ └── README.md ├── homography-mapping/ │ ├── demo.py │ ├── demo2.py │ ├── demo3.py │ ├── homography-tutorial.ipynb │ ├── images/ │ ├── output/ │ └── README.md ├── mask-rcnn/ │ ├── Basketball_Mask_RCNN.ipynb │ ├── mask_rcnn_video.py │ ├── mask_rcnn.py │ ├── images/ │ └── README.md ├── mini-map-tutorial/ │ └── README.md ├── .gitignore ├── LICENSE └── README.md


## Features

1. **Color Detection**: Detect and visualize team colors from basketball videos.
2. **Court Detection**: Identify and map basketball courts in video frames.
3. **Homography Mapping**: Warp basketball court views using homography techniques.
4. **Mask R-CNN**: Perform object detection on basketball players and other elements in videos.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/basketballVideoAnalysis.git
   cd basketballVideoAnalysis

2. Install dependencies for each module:
Navigate to the respective module directory (e.g., color-detection/, mask-rcnn/) and install the required Python packages:

pip install -r requirements.txt

Usage:
1) Color Detection
Run the show_colors.py script to visualize team colors:
python color-detection/show_colors.py

2) Court Detection
Use court_detection1.py to detect courts in video frames:
python court-detection/court_detection1.py

3) Homography Mapping
Explore the homography mapping examples in the Jupyter notebook:
jupyter notebook homography-mapping/homography-tutorial.ipynb

4) Mask R-CNN
Run the Mask R-CNN model on videos:
python mask-rcnn/mask_rcnn_video.py

License
This project is licensed under the Apache License 2.0.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

Acknowledgments
Mask R-CNN
Basketball Mini-Map Tutorial
