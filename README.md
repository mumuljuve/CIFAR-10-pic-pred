Michael Montanez
Lambton college

Data was collected from https://www.cs.toronto.edu/~kriz/cifar.html

Findings and Conclusions:

After 21 epochs of training, the Convolutional Neural Network (CNN) model achieved a training accuracy of approximately 77.47% and a validation accuracy of about 75.43%.
The model architecture consists of two convolutional layers followed by max-pooling and then 2 convolutional layers again with 2 dropout layers, along with three dense layers. The total number of trainable parameters is 772,304.


Recommendations for Improving Performance:

Hyperparameter Tuning: Experiment with different combinations of hyperparameters such as learning rate, batch size, number of epochs, and dropout rate to optimize the model's performance.
Data Augmentation.
Architecture Modifications: Adjusting the architecture by adding more convolutional layers or increasing the depth of existing layers to capture more complex features, or changing the amount of neurons or filters for the convolutional layers

Suggestions for Future Research:

Investigate Advanced Architectures: Explore state-of-the-art architectures like attention mechanisms, capsule networks, or self-attention mechanisms to further enhance performance.
Ensemble Methods: Experiment with ensemble techniques such as bagging or boosting to combine multiple models and improve predictive accuracy.
Explainable AI: Incorporate techniques for interpreting and explaining the model's predictions, such as attention maps or gradient-based attribution methods, to enhance model transparency and trustworthiness.
Domain-Specific Optimization: Tailor the model architecture and training procedure to the specific characteristics of the dataset, considering domain knowledge and insights to achieve better performance.
