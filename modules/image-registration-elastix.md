# elastix

## Installation

- http://elastix.isi.uu.nl/download.php
- There also is a Fiji wrapper that makes elastix easier to use: https://imagej.net/Elastix 

## Manual

http://elastix.isi.uu.nl/download/elastix_manual_v4.8.pdf

## Registration quality metrics

Various intensity based metrics; see the manual.

## Transformation types

Various transformation types; see the manual.

<img width="762" alt="image" src="https://user-images.githubusercontent.com/2157566/67085265-ce503300-f19e-11e9-82e2-ac77591728d6.png">

## Practical 

We will use the Fiji wrapper for elastix.

- Open Fiji
- Run Elastix
	- Fixed image: '../data/registration/sbem.ome.tif'
	- Moving image: '../data/registration/xray-manually-similarity-aligned.ome.tif'
	- Try whether you can improve the alignment using Similarity, Affine, or BSpline transformations
	- Tip: Use Fiji's 'Synchronize Windows' functionality to compare images in 3D
- Run Elastix
	- Fixed image: '../data/registration/sbem-segmented-neuropil.ome.tif'
        - Moving image: '../data/registration/xray-segmented-neuropil-manually-similarity-aligned.ome.tif'
        - Try whether you can improve the alignment using Similarity, Affine, or BSpline transformations
        - Tip: Use Fiji's 'Synchronize Windows' functionality to compare images in 3D



