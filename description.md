##### **Project Overview:**



Traditional blood typing relies on agglutination methods that require invasive blood collection, specialized labs, and trained professionals. This project explores the potential of fingerprint-based detection, leveraging the fact that ABO and Rh blood group antigens are present in sweat secretions of fingerprint ridges.



By applying deep learning techniques (MobileNetV2) on fingerprint images, we demonstrate an innovative solution that combines biometrics with medical diagnostics.



##### **Methodology:**



Dataset Preparation



Initial Dataset: ~6,000 fingerprint images across all major blood groups.



Data Augmentation: Expanded to ~18,000 images using transformations to improve model robustness.



Train/Validation/Test Split: 70% / 15% / 15%.



Model Architecture



MobileNetV2 (lightweight CNN optimized for image classification).



Fine-tuned on augmented fingerprint dataset.



Training Process



Input: Preprocessed fingerprint images.



Loss Function: Categorical Cross-Entropy.



Optimizer: Adam (with learning rate tuning).



Regularization: Data augmentation + dropout layers.



Evaluation Metrics



Accuracy on Training, Validation, and Test sets.



Generalization assessed with independent test set.



##### **Model Performance**



Training Accuracy: 99.53%



Validation Accuracy: 96.34%



Test Accuracy: 95.09%



These results show that MobileNetV2 achieves high generalization capability, making it a promising baseline for non-invasive blood group detection.



##### **Key Advantages:**



Non-Invasive: No needles, no discomfort.



Rapid Results: Suitable for emergency medicine and remote areas.



Dual Functionality: Combines identity verification with blood typing.



##### **Current Challenges:**



Dataset Limitations: Needs larger, more diverse population samples.



Hardware Integration: Development of portable, cost-effective fingerprint sensors.



Clinical Validation: Extensive trials required before medical deployment.



##### **Future Scope:**



Integration with portable biometric devices.



Exploration of other CNN architectures (ResNet, EfficientNet).



Deployment in forensic medicine, personalized healthcare, and emergency diagnostics.



##### **Tech Stack:**



Programming Language: Python



Frameworks: TensorFlow / Keras



Model: MobileNetV2



Environment: Jupyter Notebook / Colab

