# 🌱 Plant Disease Classification

## 📌 Project Overview
This project applies **deep learning** to detect and classify plant diseases from leaf images. Using the popular **PlantVillage dataset**, the notebook trains an image classification model to help farmers and researchers identify plant health issues quickly and accurately.  

## 📂 Repository Structure
```
├── Plant.ipynb                 # Jupyter Notebook with preprocessing, training, and evaluation
├── archive (2).zip             # Zipped dataset
│   └── PlantVillage/           # Extracted dataset folder
│       ├── Pepper__bell___Bacterial_spot/
│       ├── Pepper__bell___healthy/
│       ├── Potato___Early_blight/
│       ├── Potato___Late_blight/
│       ├── Potato___healthy/
│       └── ... more classes ...
```

## 🚀 Features
- Loads and preprocesses plant leaf images  
- Builds and trains a **Convolutional Neural Network (CNN)**  
- Classifies plant diseases into multiple categories  
- Visualizes accuracy, loss, and predictions  

## 🛠️ Requirements
Install dependencies before running the notebook:
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn opencv-python
```

## 📊 Dataset
The **PlantVillage dataset** includes images of healthy and diseased leaves from various plants such as:
- Pepper (Bell)
- Potato
- Tomato
- Others  

Each folder corresponds to a **disease category** or **healthy class**.

## ▶️ Usage
1. Extract the dataset:
   ```bash
   unzip "archive (2).zip"
   ```
2. Open the notebook:
   ```bash
   jupyter notebook Plant.ipynb
   ```
3. Run all cells to train and evaluate the model.  

## 📈 Model Output
- Training & validation accuracy/loss plots  
- Classification results  
- Example predictions with images  

## 🤝 Contributing
You can extend this project by:
- Adding more datasets  
- Testing different CNN architectures  
- Improving preprocessing techniques  

## 📜 License
This project is for **research and educational purposes** only.  
