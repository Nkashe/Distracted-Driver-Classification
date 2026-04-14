# 🚗 Distracted Driver Classification

This project implements a **deep learning model** for distracted driver detection, focusing on identifying unsafe driver behaviors using image-based classification techniques. It covers the full machine learning pipeline, including data preprocessing, model training, evaluation, and a clean, modular structure designed for reproducibility and scalability.

Distracted driving is a major cause of road accidents worldwide. This project applies deep learning to classify driver behavior and detect distractions such as phone usage, eating, or looking away from the road. The goal is to build a reliable and scalable system that can support real-world driver monitoring and safety applications.

⚠️ **Note:** Large trained model files are **not stored in this repository** due to GitHub’s 100MB file size limit. A download link is provided separately.

---

## 📁 Project Structure

```bash
Machine-Learning-5841/
├── data/                     # Raw and processed datasets
├── figures/                  # Plots, charts, and visualizations
├── notebooks/                # Jupyter notebooks for exploration and experimentation
├── reports/                  # Project reports, summaries, and documentation
├── saved_model/              # Directory for storing trained model files
├── src/                      # Source code (training, preprocessing, utilities)
├── saved_models_on_drive.txt # External link to download large model files
└── README.md                 # Project documentation
```
## 🧠 Model Description

This project uses a deep learning-based image classification model, primarily built with Convolutional Neural Networks (CNNs), to distinguish between different driver behaviors. The model is trained on labeled image data and optimized to generalize well to unseen real-world scenarios.

The pipeline includes:

Image preprocessing and normalization
Data augmentation (e.g., rotation, flipping, brightness adjustments)
Model training and fine-tuning
Evaluation using performance metrics
Model interpretation and visualization

These components work together to improve classification accuracy and ensure robustness in real-world applications.

## 🚀 How to Run This Project

Follow these steps to set up and run the project on your machine.

1️⃣ Clone the Repository
git clone https://github.com/bmpofu-create/Machine-Learning-5841.git
cd Machine-Learning-5841
2️⃣ Create and Activate a Virtual Environment
Windows (PowerShell)
python -m venv venv
venv\Scripts\activate
Mac/Linux
python3 -m venv venv
source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Download the Trained Model

GitHub cannot store large .h5 or .keras files, so the model is hosted externally.

Open the file: saved_models_on_drive.txt
Download the model from the link inside
Place it into: saved_model/

Example:

saved_model/best_model.h5
5️⃣ Run the Application (Streamlit)

If your project includes a Streamlit app:

streamlit run app.py
6️⃣ Run Training or Evaluation Scripts

Inside src/, you may have scripts like:

python src/train.py
python src/evaluate.py
python src/preprocess.py

Adjust based on your actual file names.

## ✨ Features
Deep learning model for distracted driver classification
Clean, modular project structure
Jupyter notebooks for experimentation
External model hosting for large files
Reproducible environment using requirements.txt
Ready for deployment or further research
## 📝 Notes
Large model files are not included in the repository
Use the link in saved_models_on_drive.txt to download them
Ensure the model is placed in the correct folder before running inference
🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss what you would like to modify.


---
