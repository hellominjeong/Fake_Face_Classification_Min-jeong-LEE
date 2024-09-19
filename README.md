# Fake Face Classification Project-proposal_Min-jeong-LEE

## I. Project title  
: Real and Fake Face image classification using deep learning  

## II. Project introduction  
### Project objective  
  - To improve the performance of deep learning models to classify fake and real images so that fake images are not used for malicious purposes.
### Project motivation  
#### Ensuring Information Integrity
  - Deep learning technology has been mostly used in legitimate applications such as for entertainment and education, etc., malicious users have also exploited them for unlawful or nefarious purposes.  
  - For example, high-quality and realistic fake images, videos have been created to spread misinformation and propaganda, foment political discord and hate, or even harass and blackmail people.  
  - Fake face images, often generated through technologies like deepfakes, can be used to spread misinformation and false narratives.
  - If these fake images are mistaken for real ones in news outlets or on social media, it can lead to public confusion and undermine trust.
  - It is necessary to advance technologies that can accurately distinguish between real face images and fake face images.  

## III. Dataset description 
*Data Source: https://www.kaggle.com/datasets/undersc0re/fake-vs-real-face-classification/data*  
-   The dataset consists of two categories: real face images and fake face images **(generate using GAN technology)**, and it is structured to enable classification tasks. The dataset includes a total of X images, where Y are real face images and Z are fake face images.
### Data Splitting Strategy  
  To facilitate effective model training and evaluation, the dataset has been divided into three subsets: training, validation, and test datasets.  

#### Training Dataset:  

  This subset contains about 60% of the total dataset.  
  It includes both the input images and their corresponding labels (real or fake).  
  |fake|real|
  |---|---|
|![image](https://github.com/user-attachments/assets/8ab9e62f-1284-4391-8d5e-e8b490c0d23b)|![image](https://github.com/user-attachments/assets/0e318ab2-e688-46d5-9223-6d9fb054fbb2)|


#### Validation Dataset:

  The validation set comprises about 25% of the total dataset.  
  Like the training set, it includes both input images and their labels (real or fake).  

#### Test Dataset:

  The test dataset includes about 15% of the total dataset.  
  This set contains only the input images, without any labels (ground truth).  
  Participants will use this dataset to generate predictions, and these predicted outputs will be submitted for evaluation.    

  ---
