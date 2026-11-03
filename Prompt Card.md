Create RESNET18_trial.ipynb with 9 different cells  
The code should be as concise and simple as possible  
Cell 1: Import the libraries in requirements.txt  
Cell 2: Get the images from my dataset CALTECH-101
Cell 3: Define the residual block. Use kernel_size=3, stride=1, padding=1, bias=False. Follow the path of 1.convolutional layer 2.Batch Normalization 3.RELU activation function  
Cell 4: Define ResNet18 Architecture  
Cell 5: Define Loss Function: RELU and Optimizer: ADAM  
Cell 6: Train the model by splitting a 80:20 split between training and validation sets. epochs: 30, learning rate value: 1 × 10−3, batch size: 64.  
Cell 7: Plot Training Loss and Accuracy  
Cell 8: Graph confusion matrix  
Cell 9: Print metrics on a table: Accuracy, Precision, Recall, F1-Score, MSE, MAE