# 🧠✨ Explainable Brain Tumor Classification

- This project focuses on building an AI-powered framework for the detection and classification of brain tumors using MRI scans. Beyond classification, the key objective is to make the model’s decisions transparent and interpretable through modern Explainable AI (XAI) methods.

## 🚀 Features

- 🖼️ **MRI-Based Brain Tumor Classification**  
  Classifies MRI scans into different tumor types with high accuracy.  

- 🔍 **Explainability with CAM-Based Methods**  
  See *exactly* where the model is looking! We use:  
  - **Grad-CAM** 🌟  
  - **Grad-CAM++** ⚡  
  - **Score-CAM** 🎯
  - ...

- 📊 **Visual Results in `imgs` Folder**  
  Check out how the model highlights tumor regions in your MRI scans. Clear, visual explanations for every prediction!  

## 🖼️ Sample Results

### Grad-CAM
![Grad-CAM](imgs/gradcam_result.png)

### Grad-CAM++
![Grad-CAM++](imgs/gradcam_plus_result.png)


> 💡 **Tip:** Use these visualizations to understand which regions influence the model’s predictions the most! Perfect for research, diagnostics, or just exploring AI in healthcare.
