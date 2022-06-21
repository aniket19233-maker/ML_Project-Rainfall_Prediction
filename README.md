# CSE 544 Computer Vision Project

## Yoga Pose Classification using Features Extracted from Key-Point Detection using Machine Learning and Computer Vision(T-1)

#### Work done as a part of the course CSE 544: Computer Vision by Prof. Koteshwar Rao Jerripothula.

## About the Project

#### In this project, we present a method to classify and scoresix yoga poses - Tree Pose, Warrior-2 Pose, Goddess Pose, Triangle Pose, Extended Side Angle Pose, and Dancer Poseby designing custom features from human pose key-points. Real life instruction for a large number of poses involves emphasis on angle, the shape that is being formed and the ratio of distances between body parts. To evaluate the effectiveness of our proposed features, we create a dataset for the six poses and apply ML techniques on the featuredata extracted from them. The predictions are evaluated using metrics such as accuracy and F1-score and the yogapose is scored using cosine similarity which can be used as a corrective measure by a self-learner.

#### In this project, we work on Yoga - 82 dataset and classifiy the 82 classes of poses using self designed custom features created using the keypoints obtained from the mediapipe.

## DataSet
#### [DataSet](https://drive.google.com/drive/folders/132OOTGoOD52bpGTQUeCLXDeO__KI0_gP?usp=sharing)

#### The dataset is used in the Yoga - 82 dataset paper.

![DataSet Description](https://github.com/RahulSethi070801/ML_Project/blob/main/DataSet/Description.PNG?raw=true "DataSet Description")

## EDA and Pre-Processing
#### All the plots for EDA and Pre-processing are added in the folder [EDA+Preprocessing](https://github.com/RahulSethi070801/ML_Project/tree/main/EDA%2BPreprocessing)


## Methodology 
#### We performed various ML methods and did analysis for both Oversampled and Undersampled dataset done through sklearn library.

![Pipeline](https://github.com/RahulSethi070801/ML_Project/blob/main/Methodology/Pipeline.PNG "Pipeline")


## Running the Code

#### Download the entire repository and extract all the files to a folder.<br> There are 2 python notebooks, one for Oversampled data and another for Undersampled data.<br> They can be run using 'Run All' command in the respective IDE.

#### Code for both parts : - <br> [Oversampled](https://github.com/RahulSethi070801/ML_Project/blob/main/ml_project_oversampled.ipynb) <br> [Undersampled](https://github.com/RahulSethi070801/ML_Project/blob/main/ml_project_undersampled.ipynb)

## Results and Analysis
#### Refer to [Report_28](https://github.com/RahulSethi070801/ML_Project/blob/main/Report_T28.pdf) for results and analysis(tables included)
#### All the plots for results are added in the folder [Results](https://github.com/RahulSethi070801/ML_Project/tree/main/Results)


## Contributors

- Rahul Sethi (2019266)
- Aniket Verma (2019233)
- Hardik Garg (2019040)
- Shabeg Singh Gill (2019388)
