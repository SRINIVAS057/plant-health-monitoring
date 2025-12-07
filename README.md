<h1>Plant Health Monitoring using Deep Learning Architectures</h1>

<h3>Project Overview</h3>
<p>
This project aims to develop a model that is capable of detecting plant diseases 
from leaf images across four major crops: <b>Chilli, Potato, Sunflower, and Tomato</b>.  
Each crop folder contains a dedicated Kaggle and Jupyter Notebook for preprocessing, 
CNN-based model training, evaluation, and prediction.
</p>

<h3>Motivation</h3>
<p>
Agricultural crops are highly vulnerable to fungal, bacterial, and viral infections.  
Manual inspection is slow, requires expertise, and is prone to human error.  
This model was created to:
</p>

<ul>
  <li>Enable fast and accurate plant disease detection</li>
  <li>Assist farmers with early diagnosis to reduce crop loss</li>
  <li>Utilize deep learning for scalable agricultural disease monitoring</li>
  <li>Build per-crop disease detection pipelines</li>
</ul>

<h3>Model Architecture</h3>
<p>The notebooks follow a uniform deep learning workflow:</p>

<ol>
  <li><b>Image Preprocessing</b>
    <ul>
      <li>Resizing images</li>
      <li>Normalization</li>
      <li>Augmentation (flip, zoom, rotate)</li>
    </ul>
  </li>

  <li><b>CNN Feature Extraction</b>
    <ul>
      <li>Custom CNN models</li>
      <li>Convolution → Pooling → Dense layers</li>
    </ul>
  </li>

  <li><b>Disease Classification</b>
    <ul>
      <li>Softmax output</li>
      <li>Multi-class classification</li>
    </ul>
  </li>

  <li><b>Model Evaluation</b>
    <ul>
      <li>Accuracy</li>
      <li>Loss curves</li>
      <li>Confusion matrix</li>
    </ul>
  </li>
</ol>
<h3>Dataset</h3>

<p>
Each notebook uses plant leaf datasets containing healthy and diseased samples.
</p>

<h4>Dataset Properties:</h4>
<ul>
  <li>Image formats: <b>JPG / PNG</b></li>
  <li>Multiple disease categories for each crop</li>
  <li>All images are preprocessed inside each notebook</li>
  <li>Users can replace the dataset by updating the image directory paths</li>
</ul>


<h3>Methodology</h3>

<h4>1. Data Preparation</h4>
<ul>
  <li>Load plant leaf image datasets</li>
  <li>Split into training and validation sets</li>
  <li>Apply augmentation techniques (rotation, flip, zoom, etc.)</li>
</ul>

<h4>2. Model Training</h4>
<ul>
  <li>CNN layers used for feature extraction</li>
  <li>Model compiled using <b>Adam optimizer</b> and <b>categorical cross-entropy</b></li>
  <li>Trained over multiple epochs with checkpointing</li>
</ul>

<h4>3. Model Evaluation</h4>
<ul>
  <li>Accuracy and loss curves</li>
  <li>Confusion matrix for classification performance</li>
  <li>Per-class predictions</li>
</ul>

<h4>4. Prediction</h4>
<ul>
  <li>Upload custom leaf images</li>
  <li>Model outputs the predicted disease label</li>
</ul>

<h3>Technologies Used</h3>

<ul>
  <li><b>Python</b></li>
  <li><b>TensorFlow / Keras</b></li>
  <li><b>OpenCV</b></li>
  <li><b>NumPy</b></li>
  <li><b>Matplotlib</b></li>
  <li><b>Kaggle, Jupyter Notebook</b></li>
</ul>


<h3>Results Summary</h3>

<p>
Each notebook provides detailed evaluation metrics such as:
</p>

<ul>
  <li>Training accuracy</li>
  <li>Validation accuracy</li>
  <li>Loss comparison charts</li>
  <li>Prediction samples with outputs</li>
</ul>
