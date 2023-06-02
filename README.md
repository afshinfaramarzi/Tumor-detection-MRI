# Tumor-detection-MRI

<h1 align="center"> Tumor detection from MRI images </h1>
<p>
</p>
<h2> Data set explanations: </h2>
<p>
</p>
<li> The dataset consists of MRI images of the brain captured in three different directions: axial, coronal, and sagittal. 
These images display both benign (0: negative) and malignant (1: positive) tumors. The goal is to detect and classify 
tumors as either positive or negative. The dataset is organized into two main folders: one for training data and another 
for validation data. Each folder contains two subfolders, one for images and the other for labels. The images folder 
holds the MRI images, while the labels folder contains text files in YOLO format, which provide the coordinates of 
the bounding boxes for the tumors.</li>


<h3> Pre-trained models used in this project : </h3>   
<ul>    
<li> YOLOv8  </li>
<li> Faster RCNN </li>
</ul>           
      
<p>
</p>          
<li> <strong> Important Note: </strong> To speed up the training process, I utilize the GPU provided by Kaggle. Therefore, 
the directories and paths mentioned in the script are specific to Kaggle. However, you have the flexibility to modify these
directories and paths according to your preferences if you want to run the script on a different platform or adjust the 
file locations to suit your needs.</li>          
          
