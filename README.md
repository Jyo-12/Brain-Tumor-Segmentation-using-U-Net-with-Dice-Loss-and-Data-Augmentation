# Brain-Tumor-Segmentation-using-U-Net-with-Dice-Loss-and-Data-Augmentation
🧠 Brain Tumor Segmentation using U-Net

Deep learning project for segmenting brain tumors from MRI images using U-Net.

🎯 ## Objective

Build a model to identify and segment tumor regions at pixel level.

⚙️ ## Approach
Preprocessing: resize (128×128), normalization, binary masks
Augmentation: flip, brightness
Model: U-Net (encoder–decoder with skip connections)
Loss: BCE + Dice Loss (handles class imbalance)
📊 Results
Validation Dice score ≈ 0.7+
Accurate tumor localization with minimal noise
⚠️ Key Learning

Rotation augmentation reduced performance due to MRI orientation → removed.

🚀 ## Tech Stack

TensorFlow, OpenCV, NumPy, Matplotlib

📌 ## Conclusion

Model successfully segments tumor regions and generalizes well on unseen data.
