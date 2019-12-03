# VSG-CNN
Code for Chuanxing Geng, Lue Tao and Songcan Chen "Visual and Semantic Prototypes-Jointly Guided CNN for Generalized Zero-shot and Open-set Recognition"

## Prepare Data

- Download the GBU proposed data split: [GBU](http://datasets.d2.mpi-inf.mpg.de/xian/xlsa17.zip), uncompress and rename it to 'GBU'.

- Download the CUB dataset: [CUB](http://www.vision.caltech.edu/visipedia-data/CUB-200-2011/CUB_200_2011.tgz), and uncompress it.

- Download the AWA dataset: [AWA](https://cvml.ist.ac.at/AwA2/AwA2-data.zip), and uncompress it.

- Download the APY dataset: [Annotations](http://vision.cs.uiuc.edu/attributes/attribute_data.tar.gz), [aYahoo](http://vision.cs.uiuc.edu/attributes/ayahoo_test_images.tar.gz), [aPascal](http://pascallin.ecs.soton.ac.uk/challenges/VOC/voc2008/), and uncompress them to one directory called APY.

- Download the SUN dataset: [SUN](http://cs.brown.edu/~gmpatter/Attributes/SUNAttributeDB_Images.tar.gz), uncompress it and rename it to 'SUN'.

- Put all above uncompressed datasets to the folder "data"

## Install dependencies

- This code has been tested on Ubuntu 16.04 with Python 3.7 and PyTorch 1.2.0 (gpu).
- Install [PyTorch and torchvision](http://pytorch.org/).

## Reproduce results

- `python train.py --dataset cub ` 
- `python train.py --dataset awa ` 
- `python train.py --dataset apy ` 
- `python train.py --dataset sun ` 

---- * Attention* -----------------------------------------------------------------------

This package is free for academic usage. You can run it at your own risk.

This package was developed by Lue Tao. For any problem concerning the codes, please feel free to contact Mr. Tao (tlmichael@nuaa.edu.cn) or Mr. Geng (gengchuanxing@nuaa.edu.cn).
