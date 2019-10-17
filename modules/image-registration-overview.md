# Image registration

## Motivation

### Multi-modal imaging

One can image the same specimen with multiple modalities. Overlaying those modalities can lead to new scientific insights. However, as the imaging typically takes place on different microscopes and may even be conducted on different (stereotypical) biological samples it often is necessary to register the various images.

Modality examples:
- Serial block-face electron microscopy (SBEM)
- X-ray tomography
- Second harmonic generation (SHG) microscopy
- Coherent anti-stokes raman spectroscopy (CARS)
- Fluorescence microscopy

TODO: Put pictures

## Registration techniques overview

There are many ways to register two images. Typically, one tries to find a transformation that optimally aligns one image (the moving image) to another image (the fixed image). In order quantify how "optimal" the alignment is one needs to define a quality metric.

Quality metric examples:
- Manual landmark pairs
- Intensity mean square error
- Least mutual information error

TODO: Read about mutual information

There are also different types of transformation, allowing for different degrees of deformation of the moving image. 
For example:
- Translation
- Rotation
- Translation & rotation (Euler)
- Uniform scaling
- Euler & uniform scaling (Similarity)
- Shearing
- Affine transformation (translations, scales, flips, rotations, and shears)
- B-Spline transformations

## Registration software overview

There are many different software packages that allow you to register images.
In the open-source bioimage analysis field, popular registration packages include:
- BigWarp (Java, ImageJ)
- EC-CLEM (Java, IcY)
- Elastix (ITK, C++, binaries)

