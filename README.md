# WESPE: Weakly Supervised Photo Enhancer for Digital Cameras
TensorFlow implementation of "WESPE: Weakly Supervised Photo Enhancer for Digital Cameras"

## First step
- Download the pre-trained [VGG-19 model](https://drive.google.com/file/d/0BwOLOmqkYj-jMGRwaUR2UjhSNDQ/view?usp=sharing) and put it into `vgg_pretrained/` folder
- Download [DPED dataset](http://people.ee.ethz.ch/~ihnatova/#dataset) (patches for CNN training)     and extract it into `dped/` folder.

## Train the model
- python train_model.py model=<model> or sh train.sh
  
## Training results  
test PSNR for iphone is about 18 dB, similar to the original paper, 18.11 dB
