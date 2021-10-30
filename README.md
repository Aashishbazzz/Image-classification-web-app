# Image-classification-web-app

A image classifier web app which classfifies whether the uploaded image is "Sunflower", "Ruby ball" or "Ice cream cone".

<h3>Steps in building the application:</h3>
  1. Web scrapped the required images from "bing.com" using "bing_image_downloader".
  2. Preprocess the data.
  3. Used SVM for model training.
  4. Got 96.3% accuracy on testing data.
  5. Saved the model as a pickle file.
  6. Created a web app using streamlit.
  7. Integrated ML model with the streamlit app.
  
  
<h3>Libraries used:</h3>
  pandas
  numpy
  matplotlib
  sklearn
  bing_image_downloader
  os
  skimage
  pickle
  pyngrok
  streamlit
  
  
<h3>Installation and working</h3>
  1. clone the repository
  2. Navigate to the directory containing "app.py"
  3. Open CMD
  4. Run command "streamlit run app.py"
  5. It will provide you a URL.
  6. Navigate to that URL in your browser.
  7. It will take you to the web app.
  8. Upload the target image using the "Upload image" button and press "predict".
  9. It will show you the percentage of how much the uploaded image is related to the giveb categories.
