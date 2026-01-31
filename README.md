# Dual-Path-Feature-Extraction-
DualPathTransformer is a deep learning framework for lung cancer classification from chest CT images. The model combines dual-path CNN-based local and global feature extraction with Transformer-based attention fusion to effectively capture fine-grained details and global context. Evaluated on the IQ-OTH/NCCD dataset
## Overview
Early detection of lung cancer is critical for improving survival rates, yet accurate classification from CT images remains challenging due to subtle visual patterns. This project proposes a hybrid CNN–Transformer architecture that models both local spatial details and global semantic context for robust lung cancer classification.

## Model Architecture
- **Local Path**: ResNet18-based CNN for extracting fine-grained spatial features  
- **Global Path**: ResNet18-based CNN for capturing global contextual information  
- **Fusion**: Transformer Encoder with a learnable classification token  
- **Output Classes**: Normal, Benign, Malignant  

##  Dataset
- **IQ-OTH/NCCD Lung CT Dataset**
- Three classes: Normal, Benign, Malignant

##  Results
- **Validation Accuracy**:  94%
- Improved performance compared to baseline CNN-based models
- Evaluation metrics include accuracy, precision, recall, F1-score, and ROC–AUC

##  Tech Stack
- Python
- PyTorch
- Torchvision
- NumPy, Matplotlib, Seaborn
- Scikit-learn

##  How to Run
1. Clone the repository
   ```bash
   git clone <private>
