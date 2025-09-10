# Thesis-Task

A project to train and benchmark various object detection models for identifying brick kilns from Sentinel-2 satellite imagery.

### Project Details
* **Task:** Object Detection
* **Dataset:** [Delhi-Airshed Sentinel-2 Brick Kilns V1](https://www.kaggle.com/datasets/rishabhsnip/delhi-airshed-sentinel2-brick-kilns-v1)
* **Models:** YOLOv8, RT-DETR, Faster R-CNN

### Quickstart Workflow

1.  **Setup:** Download the dataset from the Kaggle link above.
2.  **Split Data:** Run `split_dataset.py` to create `train`, `val`, and `test` sets.
3.  **Convert Format:** For Faster R-CNN, run `yolo_to_coco.py` to convert YOLO `.txt` labels to COCO `.json`.
4.  **Train & Evaluate:** Run the training scripts for each model to get performance metrics.

