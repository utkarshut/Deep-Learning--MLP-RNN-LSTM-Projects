## Detect_Natural_Disaster

In this project we will detect natural disaster images with the help of CNN

Steps involved

### Data collection & labelling

Using selenium collected various images for earthquake ,fire ,flood  and label it accordingly

### Image Augmentation

Performed Image Augmentation to generate different augmented images

### Model Training

**Train model created from Scratch**
Designed model from scratch to predict disaster images

[Notebook](https://github.com/utkarshut/Deep-Learning--MLP-RNN-LSTM-Projects/blob/master/CNN%20--%20Mini%20-Project/Detect_Natural_Disaster/Detecting_Natural_Disaster_From_Scratch.ipynb)

**Evaluation**
<img src="./output_images/result_of_train_from_scratch.png" alt="Final Output"/>

**Train model created using VGG16 model and changing softmax layer**
Trained VGG16 model softmax layer to predict disaster images

[Notebook](https://github.com/utkarshut/Deep-Learning--MLP-RNN-LSTM-Projects/blob/master/CNN%20--%20Mini%20-Project/Detect_Natural_Disaster/Detecting_Natural_Disaster_Changing_Softmax.ipynb)


**Evaluation**
<img src="./output_images/result_of_train_from_training_softmax.png" alt="Final Output"/>

**Train model created using VGG16 model and fine tuning**
Trained VGG16 model last 3 layers to predict disaster images

[Notebook](https://github.com/utkarshut/Deep-Learning--MLP-RNN-LSTM-Projects/blob/master/CNN%20--%20Mini%20-Project/Detect_Natural_Disaster/Detecting_Natural_Disaster_Fine_Tuning.ipynb)

**Evaluation**
<img src="./output_images/result_of_train_from_traing_last_three_layer.png" alt="Final Output"/>


**Final Prediction on unseen data**
<img src="./output_images/result.png" alt="Final Output"/>
