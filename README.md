# Image classification with classical methods and neural networks
## General Information
This project explores image classification using three different algorithms: Linear SVM, SVM with Radial Basis Function (RBF) Kernel, and a Multi-Layer Perceptron (MLP). The classification was performed on three distinct datasets, allowing us to evaluate and compare the performance of each model in different contexts and types of data.

## Data Description 
Fashion-MNIST:
* Size: 70,000 images (60,000 for training and 10,000 for testing).
* Description: Grayscale images, 28x28 pixels, representing 10 classes of clothing items (shirt, pants, sweater, dress, coat, shoes, t-shirt, sneakers, bag, boots).
<p align="center">
  <img src="https://github.com/user-attachments/assets/f801ae74-6ee1-4a98-aac2-e505870d0db4" alt="imagen" width="400">
</p>



**Satellite Images of Mexico**
* Size: 1,636 images.
* Description: High-quality satellite photos showing environments such as Water, Forest, City, Crops, Desert, and Mountain.
* [Database](https://drive.google.com/drive/folders/1yGcbQ6B4GoTHrbmBPHRFVF1dMFafQrpN?usp=sharing) 
<p align="center">
  <img src="https://github.com/user-attachments/assets/154c0dd6-7cc9-415d-a874-cdf7d1d93952" alt="imagen" width="400">
</p>



**Custom Images**
* Size: 2,500 images (500 per class).
* Description: Images captured from different angles and lighting conditions, showing a shoe, a cap, a cellphone, a pencil, and a book.
* Database
<p align="center">
  <img src="https://github.com/user-attachments/assets/034ae7ba-14ab-4c45-b3ba-87d16ada8db5" alt="imagen" width="400">
</p>

## Trained Models

* Linear SVM: A linear kernel SVM classifier was used for each dataset, evaluating accuracy and recall per class.

* SVM with Radial Basis Function (RBF) Kernel: An SVM with RBF kernel was implemented to capture non-linear relationships in the data, calculating accuracy and recall per class.

* Multi-Layer Perceptron (MLP): An MLP was used, adjusting the architecture to find the best configuration of layers and neurons. Accuracy and recall per class were evaluated, highlighting performance across the three datasets.

## Results

* Fashion-MNIST: The best performance was achieved by the MLP (0.884 accuracy)
<p align="center">
  <img src="https://github.com/user-attachments/assets/27d52aa8-b340-4e7a-a628-c3dbe1675cd6" alt="imagen" width="400">
</p>


* Satellite Images: The MLP again achieved the highest accuracy (0.884)
<p align="center">
  <img src="https://github.com/user-attachments/assets/05900a1e-1559-4147-9414-9fd2d3539ba5" alt="imagen" width="400">
</p>



* Custom Images: All models achieved accuracies above 0.95, with the MLP standing out for its perfect recall in several classes.
<p align="center">
  <img src="https://github.com/user-attachments/assets/d00a4ceb-59a9-4cda-b1bf-82db7ff440b3" alt="imagen" width="400">
</p>
      
