# F a c e - t o - A n i m e 

### Train
```
python GAN.py --name your_project_name --src_data src_data_path --tgt_data tgt_data_path --vgg_model pre_trained_VGG19_model_path
```
### Folder structure
The following shows basic folder structure.
```
├── data
│   ├── src_data # src data (not included in this repo)
│   │   ├── train 
│   │   └── test
│   └── tgt_data # tgt data (not included in this repo)
│       ├── train 
│       └── pair # edge-promoting results to be saved here
│
├── GAN.py # training code
├── edge_promoting.py
├── utils.py
├── networks.py
└── name_results # results to be saved here
```



## Development Environment

* NVIDIA GTX 1060
* cuda 8.0
* python 3.5.3
* pytorch 0.4.0
* torchvision 0.2.1
* opencv 3.2.0

## Reference
[1] Chen, Yang, Yu-Kun Lai, and Yong-Jin Liu. "CartoonGAN: Generative Adversarial Networks for Photo Cartoonization." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.


