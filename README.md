### Malaria Parasite Detection in Thin Blood Smear Images by Fully Retraining Pretrained Convolutional Neural Networks (NASNetMobile) 

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, Transfer Learning, NASNetMobile
Application        : Image Recognition, Image Classification, Medical Imaging, Bio-Medical Imaging
</pre>

### Description
1. Detected Malaria Parasites from thin blood smear images collected from Malaria screening research activity by National Institutes of Health (NIH) with Deep Learning (Convolutional Neural Network) specifically by retraining pretrained model NaNetMobile completely from scratch.
2. Before feeding data into model, preprocessed and augmented image dataset containing 27,558 images (337MB) by adding random flips, rotations and shears.
3. After loading pretrainied model NasNetMobile, added global max pooling, global average pooling, flattened layer to output of trained model and concatenated them. Also added dropout and batch normalization layers for regularization before adding final output layer - a dense layer with softmax activation and compiling with optimizer-Adam with learning rate-0.0001, metric-accuracy and loss-categorical crossentropy.
4. Trained for 10 iterations and attained training accuracy 96.47% and loss(categorical crossentrpy) 0.1026 and validation accuracy of 95.46% and loss 0.1385.

#### Code
<pre>
GitHub Link      : <a href=https://github.com/anjanatiha/Malaria-Detection-from-Cell-Images-using-Deep-Learning>Malaria Detection using Deep Learning (GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Malaria-Detection-from-Cell-Images-using-Deep-Learnin>Malaria Detection using Deep Learning (GitLab)</a>
Kaggle Kernel    : <a href=https://www.kaggle.com/anjanatiha/malaria-detection-using-keras-accuracy-95?scriptVersionId=11595923>Malaria Detection using Keras (Accuracy - 95%)</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Relevant Papers
<pre>
GitHub Link      : <a href=https://peerj.com/articles/4568/>Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images (peerj)</a>
</pre>
<pre>
@article{rajaraman2018pre,
  title={Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images},
  author={Rajaraman, Sivaramakrishnan and Antani, Sameer K and Poostchi, Mahdieh and Silamut, Kamolrat and Hossain, Md A and Maude, Richard J and Jaeger, Stefan and Thoma, George R},
  journal={PeerJ},
  volume={6},
  pages={e4568},
  year={2018},
  publisher={PeerJ Inc.}
</pre>

#### Dataset
<pre>
Dataset Name     : Malaria Cell Images Dataset
Dataset Link     : <a href=https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria>Malaria Cell Images Dataset (Kaggle)</a>
Original Dataset : <a href=https://ceb.nlm.nih.gov/repositories/malaria-datasets/>Malaria Datasets - National Institutes of Health (NIH)</a>
</pre>

### Dataset Details
<pre>
Dataset Name            : Malaria Cell Images Dataset
Number of Class         : 2
</pre>

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
| **Accuracy**         | 96.47%         | 95.46%        | ---       |
| **Loss**             | 0.1026         | 0.1385        | ---       |
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
Duration                : February 2019 - April 2019
Current Version         : v1.0.0.9
Last Update             : 03.14.2019
</pre>
