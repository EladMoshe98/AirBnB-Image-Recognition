# Airbnb Amenity Detection

Computer vision system that automatically identifies amenities, cleanliness indicators, and listing features in Airbnb property images — improving data accuracy and listing transparency.

## What it does

- Detects amenities (pool, gym, kitchen appliances, etc.) directly from listing photos
- Flags cleanliness and quality signals
- Combines two detection strategies for higher recall:
  - **YOLOv8** – fast, high-accuracy object detection
  - **Open-Vocabulary Detection (OVD)** – detects arbitrary categories described in natural language

## Tech Stack

- Python
- YOLOv8 (Ultralytics)
- Open-Vocabulary Detection (OVD)
- OpenCV

## Getting Started

```bash
pip install -r requirements.txt
python main.py --image path/to/listing.jpg
```

## Results

The model successfully identifies common amenities and quality signals across a range of listing photo styles and lighting conditions.
