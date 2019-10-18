# Big Warp

## Installation

Big Warp comes by default with Fiji.

## Registration quality metrics

Manual landmark pairs

## Transformation types

See screenshot below

<img width="1239" alt="image" src="https://user-images.githubusercontent.com/2157566/66990054-c5d7f980-f0c5-11e9-99bc-5a5c35e8528a.png">

## Practical 

- Open Fiji
- Open '../data/registration/sbem.ome.tif'
- Open '../data/registration/xray.ome.tif'
- Start Big Warp
	- moving image: xray
	- target image: sbem 
	- Explore Big Warp (read the help!)
	- Save your landmarks to a file
	- Print the corresponding affine and similarity transformations and save them to a file
	- Save the transformed moving image to a file
- Start Big Warp Apply
	- use the saved landmarks to also transform: '../data/registration/xray-segmented-neuropil.ome.tif'

