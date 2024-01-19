# TyreDeteriorationClassification
This task involves classifying 1854 digital images of tyres into two categories: defective and in good condition. 
The objective is to predict the quality of tires based on these images. To enhance classification performance, a Transfer Learning approach is employed, 
leveraging the pre-trained ResNet50 model.

Transfer learning is a machine learning technique that adapts a model trained on one task to a related but different task. 
In deep learning, pre-trained models on extensive datasets, such as ImageNet, serve as a starting point for tasks with limited labeled data, 
like tire image classification.

ResNet50, a convolutional neural network architecture with 50 layers, is chosen for its proven performance in various image recognition tasks. 
ResNet50 introduces residual learning, making it easier to train deep networks.

In the context of tyre condition classification, the pre-trained ResNet50 model acts as a feature extractor. 
Instead of training the entire network from scratch, the learned weights and architecture of ResNet50 are utilized to capture hierarchical and abstract
representations of features relevant to the specific task. This transfer learning approach aimed to improve the model's ability to discern between defective 
and good condition tires based on the input images.

learning_rate, batch_size, epochs, dropout_rate and dense_units were some of the hyperparameters taken into consideration for the fine tuning of the 
neural network with hopes of achieving a better classification accuracy. 
