# Image Segmentation with U-Net

This project implements U-Net architectures for semantic segmentation, comparing a vanilla U-Net with a regularized U-Net to evaluate the effect of dropout and data augmentation on generalization.
Project Objectives

# Implement U-Net from scratch for image segmentation.

- Compare baseline (vanilla) vs. regularized model performance.
- Apply dropout and augmentation to reduce overfitting.
- Visualize training curves and segmentation masks.
- Draw insights on model generalization and robustness.

  # Technologies Used
  - Python
-   PyTorch / TensorFlow/Keras (depending on notebook)
-   NumPy, Matplotlib, scikit-image
 # Results
  - Quantitative
     Vanilla U-Net: High training accuracy, but strong signs of overfitting.
     Regularized U-Net: Improved validation performance with +X% IoU (insert your exact metric if available) and more stable training curves.

  - Qualitative
     Segmentation masks from the regularized model show clearer object boundaries and better generalization to unseen samples.

 Insight: Regularization (dropout + augmentation) significantly improves segmentation quality and robustness.
  # What I Learned

    -  How to implement and train U-Net for semantic segmentation.
     - Practical experience with regularization techniques to combat overfitting.
     - How to compare models quantitatively (IoU, loss curves) and qualitatively (predicted masks).
     -The importance of visualization for debugging and model interpretation.

