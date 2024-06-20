---
### DESCRIPTION
Speech emotion recognition (SER) is an important area of research in human-computer interaction. The ability to recognize emotions from speech can improve user experience in applications such as virtual assistants, automated customer service, and sentiment analysis. Emotions affect the way we speak, and this is reflected in various acoustic features of the voice such as pitch, intensity, and rhythm. However, challenges in emotion recognition from speech include variations in the expression of emotions by different individuals and diverse recording conditions. In this project, we use Convolutional Neural Networks (CNN) to identify emotions from audio recordings, by comparing the performance of the model before and after the application of data augmentation techniques to improve the accuracy and generalization of the model.

---

### RESULTS
The evaluation results show that the Convolutional Neural Network (CNN) model trained with augmented data performs much better than the model trained without augmentation. The following are the details of the evaluation results:
1.	Model with Augmented Data:
- Train Loss: 0.0170
- Train Accuracy: 99.57%
- Validation Loss: 2.0879
- Validation Accuracy: 58.47%
- Test Loss: 2.0532
- Test Accuracy: 60.64%
2.	Model without Data Augmentation: 
- Train Loss: 0.0274
- Train Accuracy: 99.59%
- Validation Loss: 1.9010
- Validation Accuracy: 57.48%
- Test Loss: 2.1423
- Test Accuracy: 56.2%

Analysis of the results of this evaluation shows that data augmentation is more effective in improving model performance. The model trained with augmented data achieved a test accuracy of 60.64%, slightly higher than the model without augmentation which only achieved a test accuracy of 56.2%. In addition, the loss generated by the model with augmentation is also lower (2.0532) than the model without augmentation (2.1423), indicating that the model with augmentation is better able to minimize prediction errors. However, the difference in loss between train and validation makes the model overfitting.
The use of augmentation techniques such as noise addition and pitch changes add useful variations to the training data, helping the model to better recognize emotion patterns from the audio recordings. This variation allows the model to better generalize to new data, which is reflected in the increased accuracy and decreased loss in the testing stage.

---

### CONCLUSIONS
The conclusion of this project is that Convolutional Neural Networks (CNN) can be effectively used for emotion recognition from speech with excellent accuracy rates, especially when data augmentation is applied. The data augmentation technique was shown to have a significant positive impact on model performance, as seen from the evaluation results which showed a test accuracy of 60.64% for the model with augmentation compared to 56.2% for the model without augmentation. This confirms the importance of data variation in training deep learning models to improve generalization ability and model accuracy. However, the difference in loss between train and validation makes the model overfitting.
