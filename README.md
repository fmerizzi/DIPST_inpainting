# Experiments using DIPST for inpainting medieval frescoes
## The inpainting sources and masks 
Images taken with a IR sensors, manually drawn map

IR1 ----------------------------------------------------------------------- IR2 

![IR1](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-1GIF.gif)
![IR2](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-2GIF.gif)

Images taken with a color camera

Original image ----------------------------------mask----------------------------------------------style source 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop1.jpeg" width=30% height=30%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop1_mask%26image.jpeg" width=30% height=30%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop2.jpeg" width=30% height=30%>

## inpainting IR1
Style source is IR2

DIP ---------------------------------------------------------------------------------------------------- DIPST 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2011:57:52.864176stWgh-0.02dip.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2012:03:45.907329stWgh-0.02dipst.png" width=45% height=45%> 


DIPST Animation 


![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif1/gif.gif)


## inpainting IR2
Style source is IR1

DIP ----------------------------------------------------------------------------------------------------- DIPST 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/dip.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2012:28:32.855615stWgh-0.05dipst.png" width=45% height=45%> 


DIPST Animation 


![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif3/gif.gif)


## What if I use a wrong style? 
Inpainting IR using as a style source the color image 

![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif5/gif.gif)

## Inpainting a color image with large occlusion 


DIP ----------------------------------------------------------------------------------------------------- DIPST

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2014:00:44.461841stWgh-0.02.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2013:49:19.416151stWgh-0.1.png" width=45% height=45%> 


## What if I compare it with a raw style transfer on the original image? 


DIPST ------------------------------------------------------------------------------------------------ style transfer

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2013:49:19.416151stWgh-0.1.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2013:22:48.384908TMP-30.png" width=45% height=45%> 

