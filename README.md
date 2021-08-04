# Deepfake-Detection-Model

1. Introduction

    This project aims to detect Deepfake videos using deep learning using Image Feature Extraction Network - InceptionResNetV3 and LSTM. We used transfer learning to obtain the featuress of each video and the LSTM Layer is trained with the respective features.
    
2. Files Structure

          a. Deepfake Generation

          b. Deepfake_1

          c. Deepfake_2
          
          d. Deepfake_Detection_final

     Deepfake Generation : Uses First order Model for samples on deepfake generation with personalised examples to indicate the methodology and the easy ways in creating deepfakes.  [https://github.com/AliaksandrSiarohin/first-order-model](url)
     
    Deepfake_1: Frame Extraction from the dataset into respective directories of Real and Fake then classifying them further into respective sub-directories.
    
    Deepfake_2: Face extraction from the sub-directories containing the Frames and to also skip those frames which do not contain faces.
    
    Deepfake_Detection_final: Project file that trains the dataset from  sub-dir and outputs the model file. The model is then loaded and input video is given to see if it can detect a deepfake video or not from the test dataset.
    [0] for deepfake video
    [1] for Pristine/real Video

3. System Architecture

      
      ![image](https://user-images.githubusercontent.com/56883381/128206860-f7a0bf36-7235-430f-9d4c-473ca3457e38.png)


4. Contributors

      1.  [Akash Shankar](https://github.com/akashshankar07)
      2.  [Guru Dutt](https://github.com/GURU-DUTT)
      3.  Ankith Praveen
      4.  N Rafaath
