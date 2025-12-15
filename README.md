# Car Parts Detection using YOLO v11 (CDS402)

**Objective**: A computer vision project detecting 19 car part categories using YOLO v11 on the Car Parts Segmentation dataset.

## 📊 Key Results

| Metric | Score |
|--------|-------|
| **mAP@50** | **68.05%** |
| **mAP@50-95** | **52.55%** |
| Precision | 62.2% |
| Recall | 78.7% |

**Most Difficult Class**: `left_mirror` (33.35% mAP) due to small size and similarities.

## 🚀 Quick Start

**1. Installation**
```bash
pip install ultralytics pycocotools matplotlib pillow scikit-image numpy jupyter
```

**2. Running the Project**
Open the notebook and run all cells:
```bash
jupyter notebook car_parts_yolo_detection.ipynb
```
*Note: Training 100 epochs takes ~30 mins - 2 hours depending on GPU.*

## 📂 Project Structure

```
DL/
├── Car-Parts-Segmentation/        # Original Dataset
├── car_parts_yolo/                # YOLO Format Dataset
├── car_parts_yolo_training/       # Weights & Logs
│   └── weights/best.pt            # Best Model
├── car_parts_yolo_detection.ipynb # Main Notebook
├── PROJECT_RESULTS.md             # Detailed Results
└── README.md                      # This file
```

