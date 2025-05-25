# Vision Transformer vs SWIN Transformer on CIFAR-10

This repository contains a comprehensive comparison of Vision Transformer (ViT) and SWIN Transformer models on the CIFAR-10 classification task, including performance analysis and attention visualization using Grad-CAM.

## 📁 Repository Structure

### 📊 Experimental Notebooks

The repository contains multiple Jupyter notebooks implementing different experimental configurations:

| Notebook                  | Description                           | Model Configuration                                 |
|---------------------------|---------------------------------------|-----------------------------------------------------|
| **VIT_SWIN_test_4.ipynb** | Base Patch32 with Partial Fine-tuning | ViT Base Patch32 vs SWIN Base Patch4 Window7        |
| **VIT_SWIN_test_5.ipynb** | Tiny Patch16 with Partial Fine-tuning | ViT Tiny Patch16 vs SWIN Tiny Patch4 Window7        |
| **VIT_SWIN_test_6.ipynb** | Large Patch16 with Partial Fine-tuning| ViT Large Patch16 vs SWIN Large Patch4 Window7      |
| **VIT_SWIN_test_7.ipynb** | Base Patch32 with Full Fine-tuning    | ViT Base Patch32 vs SWIN Base Patch4 Window7        |
| **VIT_SWIN_test.ipynb**   | Combined Analysis and Visualization   | Comprehensive comparison with Grad-CAM              |

### 📋 Documentation

- **HW4_Report.pdf**: Complete research report with detailed analysis, methodology, results, and conclusions  
- **README.md**: This file - repository overview and file descriptions

## 🧪 Experimental Setup

### Model Variants Tested

**Vision Transformer (ViT):**
- ViT-Tiny (5.5M parameters): `vit_tiny_patch16_224`
- ViT-Base (87.5M parameters): `vit_base_patch32_224`  
- ViT-Large (303.3M parameters): `vit_large_patch16_224`

**SWIN Transformer:**
- SWIN-Tiny (27.5M parameters): `swin_tiny_patch4_window7_224`
- SWIN-Base (86.8M parameters): `swin_base_patch4_window7_224`
- SWIN-Large (195.0M parameters): `swin_large_patch4_window7_224`

### Fine-tuning Strategies

1. **Partial Fine-tuning**: Only classification head and later layers are trained  
2. **Full Fine-tuning**: All model parameters are updated during training

## 🚀 Quick Start

### Open in Google Cola

Click the buttons below to open each homework notebook in Colab:

| Homework | Colab Link |
|----------|------------|
| **Test_4**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_4.ipynb) |
| **Test_5**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_5.ipynb) |
| **Test_6**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_6.ipynb) |
| **Test_7**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_7.ipynb) |
| **Test**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test.ipynb) |

### Local Setup

```bash
# Clone the repository
git clone https://github.com/kiwiiiiiiiiO/RNN-Transformer.git
cd RNN-Transformer/HW4

# Install required dependencies
pip install torch torchvision timm matplotlib numpy pandas
pip install grad-cam opencv-python

# Run any notebook
jupyter notebook VIT_SWIN_test_4.ipynb

