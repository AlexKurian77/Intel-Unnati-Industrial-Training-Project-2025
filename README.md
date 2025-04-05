# Intel-Unnati-Industrial-Training-Project-2025  

## Retail Store Customer Analytics using Computer Vision

### 🛍️ About

A computer vision-based system that leverages YOLOv8 for customer detection and tracking in a retail store. It uses heatmaps and clustering to provide insights into customer movement, frequently visited areas, and behavioral patterns.

---

### 🔑 Features

- 👀 **Customer Detection & Tracking**  
  Real-time person detection using YOLOv8 on store video footage.

- 🗺️ **Heatmap Generation**  
  Creates a heatmap (`customer_heatmap.png`) showing footfall intensity.

- 📊 **K-Means Clustering**  
  Uses `Mall_Customers.csv` to cluster customer types and compare with video insights.

- 📽️ **Video Analysis**  
  Works with both pre-recorded videos (`video/`) and live webcam input.

- 🧾 **Script Highlights**  
  - `test.py`: Main pipeline for detection, tracking, clustering, and heatmap generation  
  - `record_video.py`: Record custom store footage using a webcam  

---

### 🚀 How to Run

1. Place your video files inside the `video/` directory.

2. Run the main script:

```bash
python test.py
```

3. (Optional) Record a video with webcam:

```bash
python record_video.py
```

---

### 📂 Outputs

| File | Description |
|------|-------------|
| `customer_heatmap.png` | Heatmap showing areas with high customer footfall |
| `Mall_Customers.csv` | Dataset used for clustering analysis |
| `output_video.mp4` (if implemented) | Annotated video showing detected customers (bounding boxes, zones) |

---

### 🛠️ Built With

- YOLOv8  
- OpenCV  
- Python  
- Seaborn, Matplotlib (for heatmaps)  
- Scikit-learn (for clustering)

---

### 🔮 Future Scope

- Real-time dashboard for store managers  
- Multi-zone behavioral analysis  
- Integration with billing and inventory systems  
- Privacy-preserving tracking (face blurring, etc.)

---

### 👨‍💻 Developers of the Project

- Alexander Kurian  
- Shraddha Bansal  
- Diya Menghani

---

### 🏫 Affiliation

CHRIST (Deemed To Be University), Delhi NCR

---
