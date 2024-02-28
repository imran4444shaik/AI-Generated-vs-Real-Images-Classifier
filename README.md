# AI-Generated-vs-Real-Images-Classifier

The provided code represents a project focused on image classification using a convolutional neural network (CNN), with additional functionality for visualizing model performance and interpreting the model's decisions.

Dataset and Data Loading: The project starts by defining a custom dataset class (CustomDataset) to load images for training, validation, and testing. Data loaders (DataLoader) are created to facilitate batch loading during training and evaluation.

Model Setup and Training: A pre-trained CNN model (specifically, RexNet-150) is chosen and fine-tuned for the image classification task. The model is trained using a training loop, where metrics such as loss, accuracy, and F1 score are calculated and monitored over multiple epochs. Early stopping is implemented to prevent overfitting.

Visualization: Various visualizations are provided to analyze the training process and model performance. Learning curves (loss, accuracy, and F1 score) are plotted to monitor the model's progress over epochs.

Class Activation Mapping (CAM): The project implements Class Activation Mapping (CAM) to visualize which regions of input images are influential in the model's predictions. CAM overlays heatmaps onto original images, highlighting the areas contributing most to the model's decisions.

Inference and Evaluation: The trained model is evaluated on a test dataset to assess its performance. Accuracy is reported, and CAM visualizations are generated for a subset of test images to provide insights into the model's behavior.

Overall, this project demonstrates a comprehensive pipeline for image classification, including data loading, model training, evaluation, and visualization techniques for understanding and interpreting model decisions.
