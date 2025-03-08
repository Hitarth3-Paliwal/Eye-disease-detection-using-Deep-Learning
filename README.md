# Eye-disease-detection-using-Deep-Learning
Eye  Disease Recognition using Deep Learning

# Overview 
The Ocular Eye Disease Detection project aims to automate the diagnosis of various eye diseases using deep learning techniques. The project utilizes the ODIR dataset, which includes fundus images of patients with Diabetes, Glaucoma, Cataract, Related Macular Degeneration, Myopia, Hypertensive Retinopathy, and other eye conditions. The objective is to build a robust and accurate system for identifying ocular diseases from fundus images.

# Image Processing
Image Processing To extract useful texture information from the fundus images, Local Binary Pattern (LBP) is applied as a preprocessing step. LBP is a powerful texture descriptor that helps capture significant patterns and features from the images, improving the performance of the models.

# Deep Learning Models
Three different deep learning models are utilized for ocular disease recognition:

VGG-19: A popular and deep convolutional neural network architecture known for its ability to learn intricate features from images. VGG-19 has shown great success in various image recognition tasks.

ResNet-50: Residual Network is another widely used deep learning architecture that addresses the vanishing gradient problem, allowing for the training of very deep networks. ResNet-50 has demonstrated excellent performance in image classification tasks.

Vision Transformer: The Vision Transformer is a recent breakthrough in computer vision, showing remarkable results in various image-related challenges. It employs a self-attention mechanism to capture global information from the images.
