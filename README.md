# Cona Detect
## Analyzing COVID-19 Patients Automatically Based on Chest X-ray Images Using a Deep Neural Network Model
### Research Festival 2020 at FPT Can Tho University
#### Team members:
1. Phan Le Trong Nghia
2. Nguyen Duc Tong
3. Dang Minh Thuan
4. Duong Tri Tin

#### Instructor: MSc. Luong Hoang Huong

##### Abstract
In this research, we propose ***Cona Detect*** , which is a CNN model, to diagnose and identify COVID-19 positive cases based on patients' chest X-ray images. ResNet101 is the architecture that has been used for the proposed model. By using a dataset prepared by collecting the chest images of COVID-19 patients and others chest pneumonia X-ray images, such as bacterial and viral problems, the proposed model will use those to train and give out the prediction of the images based on the test images, finally calculating the accuracy of the model. Cona Detect has been trained and tested on the prepared dataset and the preliminary results prove that our proposed model obtained an overall accuracy of 91.43% (using ResNet101), and more importantly, the precision and f1-score rate for COVID-19 cases are 95% and 97% respectively for 4-class cases (COVID-19 versus Normal versus Pneumonia-bacterial versus Pneumonia-viral). Overall, the proposed model essentially offers the current radiology based methodology, and during the COVID-19 pandemic, it can be a truly effective tool for diagnosis, and follow-up of COVID-19 cases, as well as identifying other pneumonia symptoms.

##### Model applied
1. Deep Neural Network (DNN)
2. Convolutional Neural Network (CNN)
3. Residual Neural Network (ResNet)

##### Diseases for experiment
* COVID-19
* Normal
* Pneumonia-bacterial
* Pneumonia-viral

##### CNN Model applued for experimental evaluation
* VGG16
* VGG19
* ResNet50
* ResNet101
* Xception
