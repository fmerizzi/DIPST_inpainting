# Effective use of DIPST in medieval inpainting

Original image --------------------------------------mask------------------------------------------------style source 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/0100_1.jpg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/0100_1mask.jpg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/0100_2.jpg" width=32% height=32%>


DIP -------------------------------------------------------------------------------------------------------------------- DIPST 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/DIP.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/DIPST.png" width=45% height=45%> 


![IR2](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/animatedGIF.gif)


# Experiments using DIPST for inpainting medieval frescoes

## The inpainting sources and masks 
Images taken with a IR sensors, manually drawn mask

IR1 ----------------------------------------------------------------------- IR2 

![IR1](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-1GIF.gif)
![IR2](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-2GIF.gif)

Images taken with a color camera

Original image --------------------------------------mask------------------------------------------------style source 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop1.jpeg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop1_mask%26image.jpeg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/DSC_0148crop2.jpeg" width=32% height=32%>

## inpainting IR1
Style source is IR2

Original-------------------------------------------DIP--------------------------------------------------------- DIPST 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-1.jpg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2011:57:52.864176stWgh-0.02dip.png" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2012:03:45.907329stWgh-0.02dipst.png" width=32% height=32%> 


DIPST Animation 


![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif1/gif.gif)


## inpainting IR2
Style source is IR1

Original-------------------------------------------DIP--------------------------------------------------------- DIPST 

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_sources/IR-2.jpg" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/dip.png" width=32% height=32%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2012:28:32.855615stWgh-0.05dipst.png" width=32% height=32%> 


DIPST Animation 


![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif3/gif.gif)

## Using the IR mask to inpaint the color image 


Original color ------------------------------------------------------------------------------------------------ DIP

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/tmp/IR-2colormid.jpg" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/tmp/2022-11-30%2013:48:46.144137stWgh-0.06.png" width=45% height=45%> 



## What if I use a wrong style? 
Inpainting IR using as a style source the color image 

![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif5/gif.gif)

## Inpainting a color image with large occlusion 


DIP ----------------------------------------------------------------------------------------------------- DIPST

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2014:00:44.461841stWgh-0.02.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2013:49:19.416151stWgh-0.1.png" width=45% height=45%> 


## What if I compare it with a raw style transfer on the original image? 


DIPST ------------------------------------------------------------------------------------------------ style transfer

<img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-21%2013:49:19.416151stWgh-0.1.png" width=45% height=45%> <img src="https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/2022-11-29%2013:22:48.384908TMP-30.png" width=45% height=45%> 


## Optimizing style only, using IR-1

![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/gif2/gif.gif)

## Animation comparing DIP and DISPT on IR-1


![DIPST](https://github.com/fmerizzi/DIPST_inpainting/blob/main/inpainting_results/dip_vs_dipst.gif)



