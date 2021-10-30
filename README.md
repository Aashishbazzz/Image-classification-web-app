# Image-classification-web-app

A image classifier web app which classfifies whether the uploaded image is "Sunflower", "Ruby ball" or "Ice cream cone".

<h3>Steps in building the application:</h3>
  <ol>
    <li>Web scrapped the required images from "bing.com" using "bing_image_downloader".
    <li>Preprocess the data.
    <li>Used SVM for model training.
    <li>Got 96.3% accuracy on testing data.
    <li>Saved the model as a pickle file.
    <li>Created a web app using streamlit.
    <li>Integrated ML model with the streamlit app.
  </ol>
  
  
<h3>Libraries used:</h3>
  <ol>
    <li>pandas
    <li>numpy
    <li>matplotlib
    <li>sklearn
    <li>bing_image_downloader
    <li>os
    <li>skimage
    <li>pickle
    <li>pyngrok
    <li>streamlit
  </ol>
  
  
<h3>Installation and working</h3>
<ol>
  <li>clone the repository
  <li>Navigate to the directory containing "app.py"
  <li>Open CMD
  <li>Run command "streamlit run app.py"
  <li>It will provide you a URL.
  <li>Navigate to that URL in your browser.
  <li>It will take you to the web app.
  <li>Upload the target image using the "Upload image" button and press "predict".
  <li>It will show you the percentage of how much the uploaded image is related to the giveb categories.
</ol>
