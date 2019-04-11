## DistNet: Generating Image Distortion Maps Using Convolutional Autoencoders with Application to No Reference Image Quality Assessment
You can find full access to our [paper](https://ieeexplore.ieee.org/abstract/document/8521680) here. In this post, we provides the trained models and example code for generating image distortion map from input natural image.

-Network architecture of the proposed DistNet as follows 
 <img alt="portfolio_view" src="https://github.com/lfovia/distnet/blob/master/models/network.jpg">

### Citation: 
If you are using the code/model/data provided here in a publication, please cite our paper:
    
    @ARTICLE{8521680,
    author={S. V. R. {Dendi} and C. {Dev} and N. {Kothari} and S. S. {Channappayya}},
    journal={IEEE Signal Processing Letters},
    title={Generating Image Distortion Maps Using Convolutional Autoencoders With Application to No Reference Image Quality Assessment},
    year={2019},
    volume={26},
    number={1},
    pages={89-93},
    doi={10.1109/LSP.2018.2879518},
    ISSN={1070-9908},
    month={Jan},}


## Pretrained models and example codes: 
Without MSCN: [pretrained model](https://github.com/lfovia/distnet/blob/master/models/model.h5) and [example code](https://github.com/lfovia/distnet/blob/master/examples/generate_dist_map.ipynb) for generating distortion map.

With MSCN: [pretrained model](https://github.com/lfovia/distnet/blob/master/models/model_mscn.h5) and [example code](https://github.com/lfovia/distnet/blob/master/examples/generate_dist_map_mscn.ipynb) for generating distortion map.


## Install prerequisites: 
Keras: https://keras.io/#installation


