# U-net-3D
Customised 3D U-net for high-resolution aortic segmentation from low resolution images

Routine clinical cardiac magnetic resonance (CMR) images, present a challenge to 3D segmentation task due to their limited resolution in certain dimensions (e.g. low-res in sagittal/coronal view when acquired in transever plane as thick slices).
This leads to most current study of aorta size focus only on slice-by-slice 2D segmentation. 
Our proposed method addresses this challenge by generating high-resolution 3D masks from low-resolution input images through learning patterns from other high-resolution image-mask pairs.
