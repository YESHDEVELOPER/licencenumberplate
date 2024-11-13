# ROBOFLOW 
(contains of the total 18528 img)
 https://universe.roboflow.com/augmented-startups/vehicle-registration-plates-trudk/dataset/2

Augmentations
Outputs per training example: 3
Flip: Horizontal
Crop: 0% Minimum Zoom, 20% Maximum Zoom
Grayscale: Apply to 5% of images
Saturation: Between -46% and +46%
Brightness: Between -25% and +25%
Blur: Up to 1px
Noise: Up to 1% of pixels

# kaggle
 For Commercial Usage: Full version of the dataset includes 1,200 000 images & OCR Annotations, leave a request on TrainingData to buy the dataset
 import kagglehub

 https://www.kaggle.com/datasets/trainingdatapro/license-plates-1-209-438-ocr-plates
# Download latest version
path = kagglehub.dataset_download("trainingdatapro/license-plates-1-209-438-ocr-plates")

print("Path to dataset files:", path)

