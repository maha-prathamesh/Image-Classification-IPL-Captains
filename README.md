# Image-Classification of IPL Captains

Goal is classsify IPL Captain Images.

<b>Step 1: Data Cleaning</b></br>
For Data cleaning we have used Open CV. Data Cleaning process contains:
1) Remove images where Open CV does not detect face and eyes.
2) Crop images and save as a dataset filtered by step 1.

<b>Step 2: Feature Engineering</b>
1) Convert image with the help of wavelet transform.
2) Combine originial image with wavelet transformed image.
3) Reshaped combined image
4) For Target variable defined each folder of player as dictionary

<b>Step 3: Model Building</b>
1) Use SVC, Random Forest, Logistic Regression with default parameter.
2) Use GridSearchCV for hyperparameter tuning.

<b>Step 4: Create API</b>
1) Saved finalize model as pkl file. Devleped API in Flask.
2) Created API which take input image in the form of BASE64 encoding text. Encoded text decoded and gave input as to OpenCV.
3) Transform it to Feature to classify.

<b>Step 5: Create client</b>
1) Use CSS, Javascript, Html to build HTML page.
2) With the help "nginx" delpoyed client mode by making changes in nginx.config


# UI Screenshots:
