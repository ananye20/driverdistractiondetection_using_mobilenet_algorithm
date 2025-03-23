# driverdistractiondetection_using_mobilenet_algorithm

Driver distraction is a leading cause of road accidents worldwide. This project leverages **MobileNetV2** and computer vision to classify 10 types of driver distractions (texting, talking, adjusting radio, etc.) using the [State Farm Distracted Driver Dataset](https://www.kaggle.com/c/state-farm-distracted-driver-detection). Achieves **~86% validation accuracy** with transfer learning and data augmentation.

## Dataset 📂  
**Source**: [Kaggle State Farm Distracted Driver Detection](https://www.kaggle.com/c/state-farm-distracted-driver-detection)  

## Technologies Used 🛠️  
- **Framework**: TensorFlow/Keras  
- **Model Architecture**: MobileNetV2 + Custom Classification Head  
- **Tools**: 
  - OpenCV (image processing)
  - scikit-learn (metrics)
  - Matplotlib/Seaborn (visualization)
  - Kaggle API (data download)
 
## Usage
### Preprocess the data:
Organize the dataset into training and testing directories.
Apply data augmentation techniques to enhance model robustness.

### Train the model:
Configure model parameters and initiate training.

### Evaluate the model:
Test the model on unseen data and analyze performance metrics.

## Model Training
The model is trained using convolutional neural networks (CNNs) to classify images into the predefined categories. Transfer learning techniques, such as utilizing MobileNet model, can be employed to enhance performance.

## Testing
After training, the model is evaluated on a separate test set to assess its accuracy in detecting driver distractions. Performance metrics such as accuracy and loss are calculated.

## Results
The trained model achieves high accuracy in classifying driver behaviors, effectively distinguishing between safe driving and various distracted activities. Detailed results and performance metrics are documented in the results section of the documentation attached.

## Contributing
Contributions are welcome! 

## License
This project is licensed under the MIT License.

Feel free to try the coding file and for more information please go through the document attached!
