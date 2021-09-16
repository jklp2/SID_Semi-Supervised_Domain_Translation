# SID_Semi-Supervised_Domain_Translation
## Environment
1. Python 3.7
2. PyTorch 1.8.0
3. CUDA 9.1
4. Ubuntu 20.04
## Dataset
Google drive: [DATASETS](https://drive.google.com/drive/folders/10cP6Z-n2G0006_ppW1WxkQpNKg3mSfnj?usp=sharing).
## Pretrained Checkpoint
Google drive: [Checkpoint](https://drive.google.com/file/d/1vHydxmBH8o5HuxVyG4ojRZWrr788zOp5/view?usp=sharing)

## Test
Put your test images in the input directory, and run:
```
python --model cra_unrolled_final --resume --ckpt_path $CKPT_PATH
```
The results are in the output directory.
## Results on several database
#### SOTS-OD
![image](imgs/sots.jpg)
#### O-HAZE
![image](imgs/o-haze.jpg)
#### DENSE-HAZE
![image](imgs/d-haze.jpg)
#### NH-HAZE
![image](imgs/nh-haze.jpg)
