# BREAST-CANCER-DETECTION
Breast cancer is the most frequent cancer among women, with around one in every 19 women at risk. The number of cases of breast cancer is gradually increasing, especially as the population ages. The mammography screening procedure has to be improved and made more efficient. When it comes to medical imaging, there is always space for improvement. Cancer patients' chances of dying are reduced if they are diagnosed early. The goal of this project is to find the identification of breast cancer using a deep learning model network. Image preparation, categorization, and performance evaluation are all part of the total process. In this research, using the Breast Histopathology Images dataset, we examine the effectiveness of the deep learning model, InceptionResnet, in classifying the presence of IDC(Invasive Ductal Carcinoma). In terms of accuracy, the trained model gave an accuracy of 91%.

# DATASET
Breast Histopathology Images, a datset available on Kaggle has been used for this project. in this, each patch’s file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png, wherehere u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.

Link: https://www.kaggle.com/paultimothymooney/breast-histopathology-images

![Capture1](https://user-images.githubusercontent.com/71033672/153760048-9915e5a7-544d-4e47-a230-bf7b3aef13a4.JPG)

# MODEL
InceptionResnet has been used for training the model.

![Capture3](https://user-images.githubusercontent.com/71033672/153760062-7b107601-468c-4473-8754-fc01ba9c093d.JPG)

# WORKING DEMONSTRATION


https://user-images.githubusercontent.com/71033672/153760747-3510dea0-479b-4c78-8f6e-a6cc81dbd288.mp4

