# 🎓 Intel Unnati 2025 - Image Super-Resolution Project

**Knowledge Distillation for Image Super-Resolution**

## 📊 Project Overview

This project implements a lightweight image super-resolution model using knowledge distillation techniques as part of the Intel Unnati Industrial Training Program 2025.

### 🎯 Key Achievements

- ✅ **92.7% SSIM Score** (Target: >90%)
- ✅ **483K Parameters** (Lightweight model)
- ✅ **Real-time Processing** up to 1920×1080
- ✅ **Knowledge Distillation** from SwinIR teacher model

## Dataset Used is uploaded in google Drive Link : https://drive.google.com/drive/folders/1S0-4pJsoOoKeGSiSCTVQCso6eTyZbri9?usp=sharing

## 🏗️ Project Structure

```
Intel_project_final_version/
├── Intel_Unnati_Project.ipynb    # Main implementation notebook
├── DIV2K_train_HR/                # Dataset (800 high-res images)
├── student_models/                # Trained model weights
├── TeacherModel/                  # SwinIR teacher model
├── data/                          # Processed training data
├── 100_enhanced_results.png       # Visual results
└── README.md                      # This file
```

## 🔧 Technical Specifications

- **Dataset:** 800 DIV2K high-resolution images
- **Architecture:** Enhanced CNN with 6 residual blocks
- **Training:** Knowledge distillation with L1+MSE loss
- **Performance:** 92.7% average SSIM, 28.5 dB PSNR
- **Scalability:** 100×100 to 1920×1080 resolution

## 📋 Requirements

```python
torch>=1.9.0
torchvision>=0.10.0
opencv-python>=4.5.0
scikit-image>=0.18.0
matplotlib>=3.3.0
numpy>=1.21.0
Pillow>=8.3.0
```

## 🚀 Usage

1. Open `Intel_Unnati_Project.ipynb` in Jupyter/VS Code
2. Run cells sequentially to:
   - Set up environment
   - Load and preprocess data
   - Train the model
   - Evaluate performance
   - Generate visual results

## 📈 Results

- **SSIM Score:** 92.7% (exceeds 90% target)
- **Model Size:** 1.85 MB
- **PSNR Score:** 28.5 dB (exceeds 25 dB target)
- **Resolution:** 1920×1080 (real-time processing)

- **Model Parameters:** 483K
- **Knowledge Distillation:** Implemented
- **Teacher Model:** SwinIR (Swin Transformer)
- **Success Rate:** 87% of images achieve >90% SSIM

## 🏆 Intel Unnati Requirements Met

- ✅ Knowledge distillation implementation
- ✅ 100×100 patch training
- ✅ 1920×1080 scalability testing
- ✅ Performance target exceeded
- ✅ Lightweight model achieved

## 👨‍💼 Author

**Team:** Code triplets  
**Program:** Intel Unnati Industrial Training 2025  
**Project:** Knowledge Distillation for Image Super-Resolution

---

_Project Status: ✅ SUCCESSFULLY COMPLETED_
