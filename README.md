# Detecting_Pneumonia_using_CNN
Building a Convolutional Neural Network to detect pneumonia using chest x-rays images.

![1*ByIYtOjD3nlCvP09xba38w](https://user-images.githubusercontent.com/76842663/149012439-d3389307-509d-41f0-8f35-8eff59bac8d5.jpeg)

# Problem Definition
One of the important diagnostic factor for pneumonia detection is x-rays images on the chest and lungs, it appears to us the importance of creating a machine learning model that is able to differentiate between infected x-ray images and other uninfected x-ray images.
# What is Pneumonia?
Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia. Pneumonia can range in seriousness from mild to life-threatening. It is most serious for infants and young children, people older than age 65, and people with health problems or weakened immune systems. Chest X-ray, blood tests, and culture of the sputum may help confirm the diagnosis. The disease may be classified by where it was acquired, such as community- or hospital-acquired or healthcare-associated pneumonia.
# Dataset description
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal). Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care. For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.
![1*J5wUMztRXZ_eHimMxULAnA](https://user-images.githubusercontent.com/76842663/149011212-5a2fb511-c934-4a71-90d5-7551564415a9.png)
# Model used :
Convolutional Neural Network
