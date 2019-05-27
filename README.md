# Pascal-VOC-Classfication-CNN
## Requirements:
* Python 3 !!
* Pytorch version 1.1  
* OpenCV version > 3  
* scipy version > 1  
* VOCdevkit 2007 (the script voc2007 inside mainscripts can be used to    download the database)

Note: you can also import the conda environment i am using:
```
docs/environment.yaml
```
## Instructions
just run the script:
```
sh ./mainscripts/trainANDeval.sh 
```

## Result:
| Arch | epochs | result |
|:-:|:-:|:-:|  
| AlexNet | 160 | 55.141% |

#### Training  took 4 hours running on Nvidia 1070 !... trainging on CPU is not recommended.
