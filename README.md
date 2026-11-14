<p align="justify">

MFC-Net is a deep learning-based framework designed for automated multiclass classification of renal diseases using CT scan images. The model classifies four categories: **Normal, Cysts, Tumors, and Stones**.

The proposed architecture integrates three pretrained CNN backbones — **EfficientNetB3, MobileNetV2, and Xception** — through a custom Multi-Head Attention mechanism to fuse complementary feature representations. This approach emphasizes important spatial and textural features while reducing irrelevant background information.

To address class imbalance in medical imaging datasets, **Focal Loss** is incorporated to improve learning across minority classes. The model is evaluated on a CT Kidney Dataset containing **12,446 images** and compared against five baseline architectures: ResNet50, DenseNet121, MobileNetV2, Xception, and EfficientNetB3.

MFC-Net achieves a **99.95% weighted F1-score**, outperforming the best baseline result of 99.84%. Furthermore, model interpretability is investigated using **Grad-CAM and Grad-CAM++**, providing visual explanations of the regions influencing classification decisions.

**Key Features**
- Four-class renal disease classification.
- Multi-backbone CNN feature fusion.
- Custom Multi-Head Attention mechanism.
- Focal Loss for class imbalance handling.
- Comparative evaluation against five pretrained CNN architectures.
- Explainable AI using Grad-CAM and Grad-CAM++.
- High-performance automated CT image classification.

**Technologies:** Python, TensorFlow/Keras, Deep Learning, CNN, Transfer Learning, Multi-Head Attention, Focal Loss, Grad-CAM, and Grad-CAM++.

**Objective:** To develop an accurate and explainable computer-aided diagnostic framework that supports renal disease identification through medical image analysis.
</p>
