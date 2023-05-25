<h1 align="center">
Simple Teachable Machine
<br>
<span>┄</span>
</h1>

## About App
This app is motivated from google <a href="https://teachablemachine.withgoogle.com/train/image">Teachble Machine</a>. Simple Teachable Machine can train deep learning model directly for images classification. The model is built from some layers of convolution (Conv2D) and fully-connected layer (FCL) which is integrated into MobileNetV2. MobileNetV2 is a architecture of deep learning that small, efficient and fast to train the model. Visit this <a href="https://achmadbauravindah-teachable-machine-streamlit-app-xvaa1a.streamlit.app/">link</a> to open the app  

## Requirements
 - Tensorflow (v2.10.0+)  <a href="https://www.tensorflow.org/install">↗️</a>
 - Streamlit (v1.21.0+)  <a href="https://docs.streamlit.io/library/get-started/installation">↗️</a>

## How to Use 
1. Clone this repository into your local machine
2. Enter to your virtual environment (optional)
3. Install requirements
4. Open Terminal and Enter to app folder which you have clone
5. Run this command `streamlit run app.py`

## Tutorial
1. Open <a href="https://achmadbauravindah-teachable-machine-streamlit-app-xvaa1a.streamlit.app/">Simple Teachable Machine</a>
2. Input the number of your image classes/labels
3. Input the class images and images itself
4. Click 'Training Model' button
5. If you want to custom hyperparameter of model training, click 'Advanced' and set (optional)
6. After model training is done, then you can classify 1 image
7. Open 'Sidebar' to analysis the evaluation of model training
8. Click link 'Download Model .h5' at sidebar to get trained model

## Example Tutorial (Food Classification)
![Example Tutorial Simple Teachable Machine](tutorial_tm.gif)