# Student Behavior Detection using YOLOv11

This project uses YOLOv11 for detecting multiple classroom behaviors from images using the SCB5 dataset.

## 📊 Best Results Achieved
| Behavior Class            | Accuracy (mAP@100) |
|--------------------------|-------------------|
| Blackboard Screen Reverse| 98.5%             |
| Blackboard + Teacher     | 93.5%             |
| Talking Teacher Behavior | 82.7%             |
| Student Writing          | 72.0              |
| Student Standing         | 67.4              |
| Group Discussion         | 61.2              |


## 🧠 Key Features
- Custom YOLOv11 training on class-specific data
- Fine-tuned on SCB5 image dataset using Google Colab
- Data augmentation and balancing for improved accuracy
- Results validated using mean Average Precision (mAP)


## 🔗 SCB5 Dataset
https://drive.google.com/drive/folders/1owY_qxVOLHnDfFELqjAtAQ4q7RrdFMU6?usp=drive_link

## 📁 Outputs
Sample predictions are in `/images/`. Full model weights and logs are on [Google Drive](https://drive.google.com/yourlink).
