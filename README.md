
## Covid-19 Detection
- Used custom-made CNN architecture for this detection.
- The accuracy achieved was around 93%.

## Brain Tumour Detection
- Used VGG-16 for feature extraction.
- Used custom-made CNN ahead of CNN.
- The accuracy achieved was around 100% (just tested on 10 images).

## Breast Cancer Detection
- Used Random Forest for this use case.
- The accuracy achieved was around 91.81%.

## Alzheimer Detection
- Trained CNN architecture for this use case.
- The accuracy achieved was around 73.54%.

## Diabetes Detection
- Used Random Forest for this use case.
- The accuracy achieved was around 66.8%.

## Pneumonia Detection
- Used custom CNN architecture for this use case.
- The accuracy achieved was around 83.17%.

## Heart Disease Detection
- Used XGBoost for this use case.
- The accuracy achieved was around 86.96%.

### Main Page
<img width="813" alt="Screenshot 2024-06-13 at 7 30 25 PM" src="https://github.com/anthonysandesh/all_in_one_healthcare/assets/52021528/5da7c3e6-6605-4a59-b1ec-59224d853abf">

### Result Page
<img width="814" alt="Screenshot 2024-06-13 at 7 30 34 PM" src="https://github.com/anthonysandesh/all_in_one_healthcare/assets/52021528/5276ac19-393e-4823-9c5f-1932c5e670f6">



## How to run this:

conda create -n healthcure python=3.9.13  

conda activate healthcure 

pip install opencv-python==4.5.1.48 numpy tensorflow==2.12.0 scikit-learn==0.24.2 imutils==0.5.4 flask==3.0.0 xgboost==2.0.3


flask run
