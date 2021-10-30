# Image-classification-web-app

A image classifier web app which classfifies whether the uploaded image is "Sunflower", "Ruby ball" or "Ice cream cone".

<h3>Steps in building the application:</h3>
  <ol>
    <li>1. Web scrapped the required images from "bing.com" using "bing_image_downloader".
    <li>2. Preprocess the data.
    <li>3. Used SVM for model training.
    <li>4. Got 96.3% accuracy on testing data.
    <li>5. Saved the model as a pickle file.
    <li>6. Created a web app using streamlit.
    <li>7. Integrated ML model with the streamlit app.
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
  <li>1. clone the repository
  <li>2. Navigate to the directory containing "app.py"
  <li>3. Open CMD
  <li>4. Run command "streamlit run app.py"
  <li>5. It will provide you a URL.
  <li>6. Navigate to that URL in your browser.
  <li>7. It will take you to the web app.
  <li>8. Upload the target image using the "Upload image" button and press "predict".
  <li>9. It will show you the percentage of how much the uploaded image is related to the giveb categories.
</ol>
