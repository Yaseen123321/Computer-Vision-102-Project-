
# Face Mask Detection

## Setup Instructions
Take the image as input.

Apply a CNN-based face detection method to locate facial features.

Crop the detected face region and resize it to 224×224 pixels to standardize input size.

Feed the resized face into the CNN classification model for mask detection.

The model outputs the result and displays a bounding box around the face with the appropriate label: mask or no mask.

## Datasets 
With Mask (Filename: 6900): https://esigelec-my.sharepoint.com/personal/cabani_esigelec_fr/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fcabani%5Fesigelec%5Ffr%2FDocuments%2FMaskedFaceNetDataset%2FCMFD&ga=1

Without/Incorrect Mask (Filename: 6900): https://esigelec-my.sharepoint.com/personal/cabani_esigelec_fr/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fcabani%5Fesigelec%5Ffr%2FDocuments%2FMaskedFaceNetDataset%2FIMFD%2F69000&viewid=a387fcc6%2D9026%2D480c%2Db9b5%2D8e0bb86764bd&ga=1
