#PCBDetectionUsingYolo12
#Project: PCB Failure Detection and Analysis at EOL based on YOLOv12



###The objective of this project is to find out the failure reason of the PCB and optimize the accuracy of the model by fine-tuning with different pre-train models. The dataset used is from PKU-Market


###Input：images dataset of the failure PCB；Output：the reason of failure（short, open, missing hole, mouse bite, spurious copper)
###dataset: https://robotics.pkusz.edu.cn/resources/dataset/

###Process:
####1. Preprocess the image data
####2. Split the dataset into train, validation and test. Using pretrain model to train the model, then optimize it using best hyperparameters. Test on the test data.
####3. Evaluation matrix includes precision, recall, F1 score
