# Custom-Image-Classifier
https://colab.research.google.com/drive/1xat6LKK3eZvXicXw8TwKTYDRKGZukSz3?usp=sharing
Visualization & Overfitting

1. What signs indicated overfitting in your first model?
The first sign of overfitting was that the training accuracy was very high while the validation accuracy was much lower. This means the model learned the training data too well but could not perform well on new or unseen data. Another sign was that the validation loss started increasing while training loss kept decreasing, showing the model was memorizing instead of generalizing.

2. How did data augmentation affect validation accuracy?
Data augmentation improved the validation accuracy because it created more variations of the training images, such as rotated, flipped, or shifted versions. This helped the model learn more general patterns and prevented it from memorizing the exact training images.

Model Improvement

3. What is the purpose of dropout layers?
Dropout layers help prevent overfitting by randomly turning off some neurons during training. This forces the model to learn multiple ways to recognize patterns instead of relying too heavily on specific neurons.

4. Why does data augmentation improve generalization?
Data augmentation improves generalization because it increases the diversity of the training data without collecting new data. By seeing many variations of the same images, the model learns the important features instead of memorizing specific examples.

Performance Comparison

5. Compare accuracy before and after improvements.
Before improvements, the model had high training accuracy but lower validation accuracy, which indicated overfitting. After adding techniques like dropout and data augmentation, the validation accuracy increased and became closer to the training accuracy, showing better performance on unseen data.

6. Which technique contributed most to improvement?
The technique that contributed most was data augmentation, because it increased the variety of training samples and helped the model learn more robust features. Dropout also helped by reducing overfitting, but augmentation had a stronger impact on validation performance.

Deployment & Application

7. Why is saving the model important?
Saving the model is important because it allows us to reuse the trained model later without retraining it. It also makes it possible to deploy the model in applications, share it with others, or continue training from the saved version.

8. How can this model be deployed in a real-world system?
The model can be deployed by integrating it into an application or system such as a web app, mobile app, or embedded system. For example, it can be connected to a user interface where users upload an image, and the system uses the trained model to predict and display the result automatically.
