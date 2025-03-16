# Neuroflux

### Overview
Neuroflux is a multimodal Grad-CAM-enhanced U-Net-based deep learning model for Glioblastoma Multiforme segmentation

### Running the Project in Google Colab
1. Navigate to neuroflux.ipynb and select **Open in Colab**
2. Select **File > Save a Copy in Drive**
3. Run the notebook with **Runtime > Run all**

### Additional Notes
1. **GPU Support:** Google Colab provides free GPU access, so using Colab will accelerate training. Ensure the Colab runtime is set to GPU by selecting Runtime > Change runtime type > Hardware accelerator > GPU.
2. **Model Output:** The notebook will generate segmented images and Grad-CAM heatmaps showing the areas of the brain where the model is focusing.

### Contributions
Feel free to fork the repository and submit a pull request with any improvements. If you have any questions or run into issues, create an issue in the GitHub repository, and we will be happy to assist you!


### Performance
Model evaluation on the test set:
==================================
Loss : 0.0358
Accuracy : 0.9886
MeanIOU : 0.5
Dice coefficient : 0.4468
Precision : 0.9906
Sensitivity : 0.9867
Specificity : 0.9968
Dice coef Necrotic : 0.2627
Dice coef Edema : 0.5072
Dice coef Enhancing : 0.4482
