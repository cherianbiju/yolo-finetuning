# YOLOv8 Fine-tuning (Football Player Detection)

Fine-tuned YOLOv8s on a custom football dataset to detect players and football in images and videos.
The pipeline covers data preparation, training, and inference on both images and videos.

## Pipeline
- Custom train/val split (80/20) from raw dataset
- Fine-tuned `yolov8s.pt` on football data
- Inference on test images and video footage

## Results
- Player detection confidence: **0.80 – 0.90+**
- Tested on images and video (352 frames)

## Dataset
Custom football dataset in YOLO format.  
📁 [Google Drive Link](https://drive.google.com/drive/folders/1Tt9dj3MrvCyHxuFvCIasc2q2QIdH-rQa?usp=sharing)

## How to Run
1. Open `yolo_finetuning.ipynb` in Google Colab
2. Mount Google Drive
3. Place dataset in the path mentioned in `dataset.yaml`
4. Run all cells

## Requirements
```
pip install ultralytics
```
## Sample Result 
![Detection Result](https://github.com/user-attachments/assets/92b32577-ebfb-46ab-bf96-bd084cc0594c)

