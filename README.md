# **Single-panorama classification of 3D objects using horizontally stacked dilated convolutions**

**Abstract**

This paper presents a single-image approach for classifying 3D objects represented as meshes. Our method centers a virtual spherical camera at the centroid of the object and casts omnidirectional rays. 
Then, it computes local geometry information of each ray's first and last intersection points, generating a single multi-channel equirectangular (ERP) image per object. We propose a convolutional block 
named Horizontally Stacked Dilated Convolution (HSDC) with different dilation rates to handle ERP distortions, and introduce a classifier built upon these blocks. Our experiments in popular 
datasets show that the results produced by our method are competitive or better than state-of-the-art voxel- and point-based methods, being the best among single-view approaches. 


Implementation will be available soon.
