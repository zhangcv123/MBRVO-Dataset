# MBRVO: Constructing Blur Robust Visual Odometry Based on Blurring Artifacts  

  
This motion blur dataset was synthesized using Unreal Engine 5. The dataset contains **230,000 sharp and blurred image pairs**,
in addition we also provide the groundtruth **optical flow**, **depth**, and **camera trajectory**.  

  
# MBR-Dataset  

Currently, only a portion of the sequences of this motion blur dataset is publicly available. We will open source the full dataset when the paper is accepted.
 Click on this link to download the test data. 
 【Baidu】  https://pan.baidu.com/s/1JNKzgmytF8yhRwvHnEMzGQ?pwd=jj2s     Password: jj2s 
 【Google】 https://drive.google.com/drive/folders/12DNUOU8DFfUSkbXx4wY5p-54-MUKD6f1?usp=sharing

## Demo  
============Blur Image=====================Sharp Image===========  
![blur image](https://i.postimg.cc/zDFFnhM0/blur.gif)
![image](https://i.postimg.cc/cHK58tGM/sharp.gif)  

  
===========Optical Flow=======================Depth=============  
![image](https://i.postimg.cc/hP0Mv17R/optical.gif) 
![image](https://i.postimg.cc/LsG3wyGL/depth.gif)

  
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
# MBRVO-Dataset
