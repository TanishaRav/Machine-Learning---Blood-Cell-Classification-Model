# 🩸 Blood Cell Classification using Deep Learning

A machine learning project that automatically identifies different types of blood cells from microscope images using deep learning.

## 🎯 What This Project Does

This model looks at blood cell images and classifies them into **8 different types** of cells:

- **Basophil** - Helps with allergic reactions
- **Eosinophil** - Fights off parasites
- **Erythroblast** - Baby red blood cells
- **Immature Granulocytes** - Young white blood cells
- **Lymphocyte** - Your immune system's soldiers
- **Monocyte** - The biggest white blood cells
- **Neutrophil** - The most common defenders
- **Platelet** - Helps your blood clot

## 📊 Data Used

The **BloodMNIST dataset** contains over **17,000 microscope images** of blood cells. Each image is 28x28 pixels.

- Training images: 11,959
- Validation images: 1,712  
- Test images: 3,421

## 🤖 The Model

Built a Convolutional Neural Network (CNN) with:
- 3 layers of convolutions to detect patterns
- Dropout to prevent overfitting
- Batch normalization for stable training
- Around **620,000 parameters** total

**Training Results:**
- 🎯 **Training Accuracy**: 95.53%
- ✅ **Validation Accuracy**: 92.17%
- ⏱️ **Training Time**: ~15 minutes (43 epochs)
- 🏆 **Best Model**: Saved at epoch 33

## 🛠️ Built With

- **Python** - Programming language
- **TensorFlow/Keras** - Deep learning framework
- **Google Colab** - For free GPU training
- **MedMNIST** - Medical image dataset
- **Matplotlib/Seaborn** - For visualizations

## 📈 Results

The model achieved **95% test accuracy** with reliable classification across all cell types. Training was smooth with early stopping preventing overfitting.

**Key Metrics:**
- Training accuracy: 95.53%
- Validation accuracy: 92.17%
- Test accuracy: 95.00%
- Model converged in 43 epochs (best at epoch 33)
