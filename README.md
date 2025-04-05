# Intel-Unnati-Industrial-Training-Project-2025  
## Retail Store Customer Analytics using Computer Vision

### Overview

This project analyzes customer behavior in a retail environment using computer vision and deep learning techniques. It applies object detection, clustering, and heatmap generation to extract insights from video footage of store activity.

### Project Structure

```
├── archive/                  # Contains archived project resources
├── video/                    # Video assets for analysis
├── yolo_files/               # YOLOv8 model files and config
├── archive.zip               # Compressed archive of resources
├── video.zip                 # Compressed video files
├── Mall_Customers.csv        # Dataset for clustering analysis
├── customer_heatmap.png      # Generated heatmap image
├── record_video.py           # Script to record video using webcam
├── test.py                   # Main script for detection, tracking, and analysis
├── README.md                 # Project documentation
```

### Features

- Customer detection using YOLOv8  
- Heatmap generation for footfall analysis  
- K-Means clustering to identify shopping zones  
- Real-time or recorded video analysis  
- Simple webcam-based video recording (`record_video.py`)

### Dependencies

- Python 3.x  
- OpenCV  
- Ultralytics (YOLOv8)  
- NumPy  
- Matplotlib  
- scikit-learn  

### How to Run

Run the main analysis script:

```bash
python test.py
```

To record a new video using your webcam:

```bash
python record_video.py
```

### Notes

- `Mall_Customers.csv` is used to demonstrate clustering behavior and compare with real-time video-based analytics.
- `customer_heatmap.png` is an example of the generated heatmap showing customer movement and concentration zones.

---
