# Building Surface Damage Analysis

## Project Overview
This project detects cracks in building surface images using OpenCV image segmentation techniques.

## Features
- Crack detection using Canny Edge Detection
- Defect density calculation
- Minor/Major damage classification
- Multiple image comparison

## Technologies Used
- Python
- OpenCV
- NumPy

## How to Run

1. Install dependencies:
pip install opencv-python numpy matplotlib

2. Place images inside images/ folder

3. Run:
python crack_detection.py

## Output
- Processed images stored in results/
- Console displays defect density and classification

## Damage Classification
If defect density < 0.02 → Minor Damage  
If defect density ≥ 0.02 → Major Damage
