# Football instance segmentation

This is a simple project ,to segement football players from a image using DeepLabV3+, as a part of ASDC company training .
the dataset is from [here](https://www.kaggle.com/datasets/mohammednomer/semantic-segmentation)
the data contains 100 images of football players and their masks.


## Requirements
- Python 3.6
- Pytorch 1.4.0
- Torchvision 0.5.0
- Pillow 7.0.0
- Numpy 1.18.1
- Matplotlib 3.1.3
- Tqdm 4.42.1
- Pandas 1.0.1
- Tensorboard 2.1.0
- Torchvision 0.5.0
- Opencv-python

## Usage
- Clone this repository
- Download the dataset from [here](https://www.kaggle.com/datasets/mohammednomer/semantic-segmentation)
- Extract the dataset in the root folder
- Run the notebook `instance_segmentation.ipynb`
- The best model will be saved in your PWD folder

## Results
the model was trained for 15 epochs and the results are as follows:   
-the validation mIoU is 0.7
-the validation Pixel Accuracy is 0.73
-the validation loss is 0.3
