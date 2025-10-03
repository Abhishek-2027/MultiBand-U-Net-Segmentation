# MultiBand-U-Net-Segmentation
demonstration of Unet model

## 📌 Overview
This project implements a U-Net architecture for image segmentation tasks.  
The model is trained to generate segmentation masks from multi-channel input images (e.g., 5 bands).

---

## 📂 Project Structure
├── data/ # Dataset (images and masks)
├── models/ # Saved models (.pth or .h5)
├── src/ # Source code (U-Net, training, evaluation)
│ ├── unet.py # U-Net architecture
│ ├── train.py # Training script
│ ├── evaluate.py # Evaluation script
│ └── utils.py # Helper functions
├── outputs/ # Generated masks and logs
├── requirements.txt # Python dependencies
└── README.md # Project documentation 
---

## 🚀 Features
- U-Net architecture implemented in  **TensorFlow**.
- Supports **multi-channel inputs** (e.g., 5 bands).
- Binary mask generation with thresholding.
- low and very basic augumentaion 
- Evaluation metrics: Accuracy, IoU, Dice Score, MCC.
- Visualization of predictions.
<img width="723" height="627" alt="Basic-UNet-architecture" src="https://github.com/user-attachments/assets/db2bd52e-0330-46c8-a036-4fabf653298e" />

---

## ⚙️ Installation
Clone this repository and install dependencies:
```bash
git clone https:https://github.com/Abhishek-2027/MultiBand-U-Net-Segmentation
cd unet-segmentation
pip install -r requirements.txt

📈 Results
Accuracy: 66%
IoU: 0.40
Dice Score: 0.55

📜 License
This project is licensed under the MIT License.

✨ Acknowledgements
U-Net original paper: “U-Net: Convolutional Networks for Biomedical Image Segmentation” by Ronneberger et al.
TensorFlow and PyTorch documentation.
