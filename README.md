Tried out YOLO11 Instance Segmentation to test how well deep learning can map rice field parcels from high-resolution imagery. The goal was to create clear field boundaries automatically, reducing the effort required for manual digitization

⚙️ Workflow in short:

• Image tiling in QGIS (Deepness plugin)

  https://plugins.qgis.org/plugins/deepness/
  
• Labeling & dataset prep in Roboflow

  https://roboflow.com/
  
• Model training & evaluation (YOLO11m-seg)

  https://docs.ultralytics.com/models/yolo11/#segmentation-coco
  
  https://docs.ultralytics.com/usage/cfg/#augmentation-settings
  
• Implemantaion the model in new data 

📊 Results:
Training showed consistent improvements in precision, recall, and mAP. The YOLO11 inference shows neat segmentation of rice fields, with red boundaries closely following the land contours. Most plots are clearly separated, though some borders remain slightly merged or less detailed. 
