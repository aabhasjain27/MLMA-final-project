# MLMA-final-project

In this project, we showcase training, evaluation, and deployment of deep learning models for retinal vein cannulation (RVC) segmentation and puncture detection using UNet and YOLOv11. Our main project files are organized as follows:

### Code/
Contains Jupyter notebooks for model training and analysis:
- **Binary_mask_unet.ipynb**: UNet model for binary mask generation
- **PunctureDetector.ipynb**: Implements a puncture detection system
- **YOLO_V11_Needle_Segmentation_Training.ipynb**: YOLO model training for needle segmentation

### Models/
Contains model artifacts, weights, and related files:
- **Weights/**: Directory for storing model weight files
- **best-new-model.pt, best.pt, unet_best_model.pth**: Trained model weights
- **model_artifacts.json**: Metadata for model configurations and training
- **roboflow_deploy.zip**: Deployment package generated by Roboflow

### Results/
Contains result artifacts, including directories for specific experiments and evaluation files:
- Experiment directories: `04.23`, `Egg06_05_TP`, etc.
- Evaluation CSV files: `test1.csv`, `test2.csv`




## Authors
Sukriti Gupta, Aabhas Jain, Krystal Lan
