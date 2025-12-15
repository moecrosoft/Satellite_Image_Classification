# Satellite_Image_Classification
- This project classifies satellite images by building Transformers in both Keras and PyTorch.
- First, the pre-trained keras CNN-Vit model and pre-trained PyTorch CNN-Vit model weights (state_dict) are loaded.
- Then the loaded model architectures are rebuilt locally so the loaded model can reconstruct the model layers.
- Then the two models are trained on the satellite image datasets to classify the images into 'agri' and 'non-agri'.
- The performances of the two models will be compared. The evaluations metrics such as accuracy, recall, f1, confusion matrix, classification report and ROC_AUC score will be compared across the two models.
- Finally, the ROC_AUC Curve for both models will be plotted for comparison
