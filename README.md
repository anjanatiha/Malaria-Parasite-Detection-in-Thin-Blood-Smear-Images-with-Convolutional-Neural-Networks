### Malaria Detection from Microscopic-Tissue Images with Deep Learning (Auto ML, NasNetMobile) 
<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, Transfer Learning, ImageNet, Auto ML, NASNetMobile
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detected Malaria from microscopic tissue images with Auto ML (Google's "NASNet").
2. For training, concatenated global pooling (max, average), dropout and dense layers to the output layer for final output prediction.
3. Attained validation accuracy of 95.72% and loss 0.1385 on 27K+ (330MB+) image cancer dataset.
</pre>

#### Code
<pre>
GitHub Link      : <a href=https://github.com/anjanatiha/Malaria-Detection-from-Cell-Images-using-Deep-Learning>Malaria Detection using Deep Learning (GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Malaria-Detection-from-Cell-Images-using-Deep-Learnin>Malaria Detection using Deep Learning (GitLab)</a>
Kaggle Link      : <a href=https://www.kaggle.com/anjanatiha/malaria-detection-using-keras-accuracy-95?scriptVersionId=11595923>malaria-detection-using-keras-accuracy-95</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Malaria Cell Images Dataset
Dataset Link     : <a href=https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria>Malaria Cell Images Dataset (Kaggle)</a>
</pre>

### Dataset Details
<pre>
Dataset Name            : Malaria Cell Images Dataset
Number of Class         : 2
</pre>

| Dataset Subtype | Number of Image | Size(MB/Megabyte)            |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 27,588          | 337 MB                       |
| **Training**    | 20,670          | ---                          |
| **Validation**  | 6,888           | ---                          |
| **Testing**     | ---             | ---                          |

| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 27,588          | 337 MB                       |
| **Training**    | 20,670          | ---                          |
| **Validation**  | 6,888           | ---                          |
| **Testing**     | ---             | ---                          |



### Model and Training Prameters
| Current Parameters   | Value                                                       |
| :------------------- | :---------------------------------------------------------- |
| **Base Model**       | NashNetMobile                                               |
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | Categorical Crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 176                                                         |                                     
| **Number of Epochs** | 10                                                          |
| **Training Time**    | 45 Min                                                      |


### Model Performance Metrics (Prediction/ Recognition / Classification)
| Dataset              | Training       | Validation    | Test      |                                 
|:---------------------|---------------:|--------------:| ---------:|
| **Accuracy**         | 96.47%         | 95.72%        | ---       |
| **Loss**             | 0.1025         | 0.1385        | ---       |
| **Precision**        | ---            | ---           | ---       |
| **Recall**           | ---            | ---           | ---       |
| **Roc-Auc**          | ---            | ---           | ---       |


### Other Experimented Model and Training Prameters
| Parameters (Experimented) | Value                                                  |
|:--------------------------|:------------------------------------------------------ |
| **Base Models**           | NashNet(NashNetMobile)                                 |
| **Optimizers**            | Adam                                                   |
| **Loss Function**         | Categorical Crossentropy                               |
| **Learning Rate**         | 0.0001, 0.00001, 0.000001, 0.0000001                   |
| **Batch Size**            | 32, 64, 176                                            |                                     
| **Number of Epochs**      | 10                                                     |
| **Training Time**         | 45 Min                                                 |

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Kaggle
Libraries               : Keras, TensorFlow, NasNetMobile
</pre>

#### Dates
<pre>
Duration                : February 2019 - Current
Current Version         : v1.0.0.9
Last Update             : 03.14.2019
</pre>
