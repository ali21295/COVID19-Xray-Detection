# COVID-19 Chest X-ray Detection Model

![Detecting Covid](https://github.com/user-attachments/assets/b6e9cb8c-f945-4315-ac71-4b91a6e30d12)
![Detecting Lung_Opacity](https://github.com/user-attachments/assets/909deb7e-f39c-4201-86d5-7b585ef7089a)

🚀 Project Overview
This project uses **Teachable Machine** to develop a deep learning model capable of detecting various conditions from **Chest X-rays**. The model identifies:
- **Healthy Chest X-rays**
- **COVID-19 Infected X-rays**
- **Lung Opacity**
- **Pneumonia Infected X-rays**

The model is trained using a dataset from the **COVID-19 Radiography Database**, including X-ray images categorized by medical experts. 

🔧 How It Works
Using Teachable Machine's easy-to-use interface, I was able to quickly train a neural network to distinguish between different lung conditions. Here's how I did it:

### Steps:
1. **Dataset Preparation**: The dataset includes labeled X-rays of patients with COVID-19, pneumonia, lung opacity, and healthy conditions.
2. **Model Training**: The model was trained with multiple iterations using **Teachable Machine's image classification tool**, leveraging its real-time feedback and training accuracy tools.
3. **Evaluation**: The model was evaluated on a separate test set, achieving **high accuracy** in detecting various conditions.
4. **Exporting**: After training, the model was exported for real-world deployment and testing.
   
🩺** Use Case**
This model has the potential to assist radiologists and healthcare professionals in the **early detection of COVID-19** and other chest infections, making diagnostic processes faster and more efficient.

🔍 **Key Features**
- **Real-time detection**: Upload a Chest X-ray and instantly see whether the patient may be infected.
- **Easy to use**: Trained and built on Teachable Machine, allowing for seamless integration and usability.
- **High Accuracy**: Thoroughly trained and tested on diverse datasets to ensure reliability.

📊 **Dataset**
The dataset used in this model is publicly available from the **[COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)** on Kaggle. It contains thousands of labeled chest X-rays, categorized into four main conditions:
- COVID-19 Infected
- Pneumonia Infected
- Lung Opacity
- Healthy

🧠 **Technologies**
- **Teachable Machine** for model training
- **Python** for data handling and deployment
- **Kaggle Dataset** for the X-ray images

🌟 **Future Improvements**
- Increase dataset size for better generalization.
- Integrate into healthcare systems for real-time diagnostic assistance.
- Deploy as a mobile app for wider accessibility.

This project is licensed under the MIT License - see the LICENSE file for details.
#TeachableMachine #AIforHealthcare #COVID19Detection #XRayAnalysis #MachineLearning #RadiologyAI #ChestXray #AIModel #OpenSourceHealth
[README.md.txt](https://github.com/user-attachments/files/17373274/README.md.txt)*****COVID-19 CHEST X-RAY DATABASE

A team of researchers from Qatar University, Doha, Qatar, and the University of Dhaka, Bangladesh along with their collaborators from Pakistan and Malaysia in collaboration with medical doctors have created a database of chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. This COVID-19, normal and other lung infection dataset is released in stages. In the first release we have released 219 COVID-19, 1341 normal and 1345 viral pneumonia chest X-ray (CXR) images. In the first update, we have increased the COVID-19 class to 1200 CXR images. In the 2nd update, we have increased the database to 3616 COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection) and 1345 Viral Pneumonia images and corresponding lung masks. We will continue to update this database as soon as we have new x-ray images for COVID-19 pneumonia patients.  


**COVID-19 data:
-----------------------
COVID data are collected from different publicly accessible dataset, online sources and published papers.
-2473 CXR images are collected from padchest dataset[1].
-183 CXR images from a Germany medical school[2].
-559 CXR image from SIRM, Github, Kaggle & Tweeter[3,4,5,6]
-400 CXR images from another Github source[7].


***Normal images:
---------------------------------------- 
10192 Normal data are collected from from three different dataset.
-8851 RSNA [8]
-1341 Kaggle [9]


***Lung opacity images:
---------------------------------------- 
6012 Lung opacity CXR images are collected from Radiological Society of North America (RSNA) CXR dataset  [8]

***Viral Pneumonia images:
---------------------------------------- 
1345 Viral Pneumonia data are collected from  the Chest X-Ray Images (pneumonia) database [9]

Please cite the follwoing two articles if you are using this dataset:
-M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, M. T. Islam, “Can AI help in screening Viral and COVID-19 pneumonia?” IEEE Access, Vol. 8, 2020, pp. 132665 - 132676.
-Rahman, T., Khandakar, A., Qiblawey, Y., Tahir, A., Kiranyaz, S., Kashem, S.B.A., Islam, M.T., Maadeed, S.A., Zughaier, S.M., Khan, M.S. and Chowdhury, M.E., 2020. Exploring the Effect of Image Enhancement Techniques on COVID-19 Detection using Chest X-ray Images. arXiv preprint arXiv:2012.02238.

**Reference:
[1]https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/#1590858128006-9e640421-6711
[2]https://github.com/ml-workgroup/covid-19-image-repository/tree/master/png
[3]https://sirm.org/category/senza-categoria/covid-19/
[4]https://eurorad.org
[5]https://github.com/ieee8023/covid-chestxray-dataset
[6]https://figshare.com/articles/COVID-19_Chest_X-Ray_Image_Repository/12580328
[7]https://github.com/armiro/COVID-CXNet  
[8]https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data
[9] https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia


***Formats
    - All the images are in Portable Network Graphics (PNG) file format and resolution are 299*299 pixels.

****Objective
    -  Researchers can use this database to produce useful and impactful scholarly work on COVID-19, which can help in tackling this pandemic. 






