# MBRVO: Constructing Blur Robust Visual Odometry Based on Blurring Artifacts  

  
This motion blur dataset was synthesized using Unreal Engine 5. The dataset contains **230,000 sharp and blurred image pairs**,
in addition we also provide the groundtruth **optical flow**, **depth**, and **camera trajectory**.  

  
# MBR-Dataset  

Currently, only a portion of the sequences of this motion blur dataset is publicly available. We will open source the all dataset when the paper is accepted.
 Click on this link to download the test data.  
【Baidu】  https://pan.baidu.com/s/1JNKzgmytF8yhRwvHnEMzGQ?pwd=jj2s     Password: jj2s  
【Google】 https://drive.google.com/drive/folders/12DNUOU8DFfUSkbXx4wY5p-54-MUKD6f1?usp=sharing

## Demo  
============Blur Image=====================Sharp Image===========  
![blur image](https://github.com/zhangcv123/MBRVO-Dataset/blob/main/demo_images/blur.gif)
![image](https://github.com/zhangcv123/MBRVO-Dataset/blob/main/demo_images/sharp.gif)  

  
===========Optical Flow=======================Depth=============  
![image](https://github.com/zhangcv123/MBRVO-Dataset/blob/main/demo_images/optical.gif) 
![image](https://github.com/zhangcv123/MBRVO-Dataset/blob/main/demo_images/depth.gif)

  
## Data Structure  

```
-Dataset
 |--train
 |    |---scenes
 |    |    |----image
 |    |    |     |-----blur
 |    |    |     |-----sharp
 |    |    |----depth
 |    |    |----optical flow
 |    |    |----poses   
 | --test
 |    |---scenes
 |    |    |----image
 |    |    |     |-----blur
 |    |    |     |-----sharp
 |    |    |----depth
 |    |    |----optical flow
 |    |    |----poses 
```
