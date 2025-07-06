# Trash Classification using Xception (Fine-Tuned)

This project uses transfer learning with the Xception CNN model to classify trash into 6 categories: cardboard, glass, metal, paper, plastic, and trash.

## 🔍 Features
- Preprocessing and data augmentation using ImageDataGenerator
- Transfer learning with frozen Xception base model
- Fine-tuning of last 20 layers of Xception for improved accuracy
- Custom image prediction
- Accuracy and loss visualization

## 📁 Files
- `Trash_Classification_Xception.ipynb`: Full Colab Notebook
- `Trash_Classification_Report.pdf`: Summary of approach and results
- `Test.jpg`: Sample test image

## 📦 Dataset
Dataset used: [Garbage Classification Dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)

## ✅ Results
Achieved up to ~88% validation accuracy after fine-tuning.

## 📌 Usage
1. Upload dataset to `/dataset_path/`
2. Run all cells in notebook
3. Test with your own image by changing the path in `img_path`

## 🧠 Future Work
- Add Grad-CAM visualization
- Deploy as web/mobile app

