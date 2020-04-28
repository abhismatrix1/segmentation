# segmentation
Image segmentation using UNET and CRF

###Introduction
This project is for image segmentation using UNET model and Conditional random field modeling.

### Getting Started

This contains jupyter notebook be be used on google colab in combination with google drive for minimum install

1. Clone [this repository](https://github.com/abhismatrix1/segmentation.git) in your local machine
2. Upload the segmentation folder (repo) on Google Drive at parent location i.e. in My Drive
3. Open segmentation.ipynb from drive using Google colab
4. Follow the steps in the notebook to train and predict labels

### Default settings
Segmantation folder contains pretrained weights. So you can do prediction without training. 

1. Run all cells and model will load pretrained model and predict on validation set.
2. To train new model set TRAIN_MODEL = True in Step - 7 of notebook


### Predict on your new image other than validation set
Follow the step to predict on your image. Step-9 in notebook is used for your image prediction. Please run all above steps before this step. 

1. Upload your jpg image on google drive inside segmentation folder at location 'My Drive/segmentation/myimages/' 
2. In Step-9 of notebook set 'image_name' variable to your image name eg. 'myimage.jpg'
3. Execute the cell and get prediction. 
4. It will give result using pretrained weights.
5. If you want to use currently trained weights the set model_path = 'model_best.hdf5' in step-9.


