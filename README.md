📊 Project Overview
- Model: Modified AlexNet with transfer learning
- Dataset: 9 date fruit varieties 
- Accuracy: 96%
- Framework: PyTorch

🏗️ Architecture
- Pre-trained AlexNet backbone (frozen feature layers)
- Custom 3-layer classifier with batch normalization
- Progressive dropout (50% → 25% → 12.5%)

📁 Files
- `dates.ipynb` - Complete training and evaluation pipeline
- `dataset/` - Date fruit images organized by variety

🔧 Key Features
- Transfer learning from ImageNet weights
- Data augmentation for robust training
- 80/20 train/validation split
- Batch size optimization for GPU efficiency
