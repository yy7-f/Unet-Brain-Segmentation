# Unet-Brain-Segmentation

Unet models optimized with the Dice Loss and binary cross entropy loss are developed for brain tumor segmentation using brain MRI images dataset. 

Dataset: 
  
The dataset contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images were obtained from The Cancer Imaging Archive (TCIA).
They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.

<img width="566" alt="image" src="https://github.com/yy7-f/Unet-Brain-Segmentation/assets/76237852/e35c9cc5-139d-4618-9b13-c902ff25f7fe">

  
Unet:  
  
Unet architecture contains four main parts and the following image illustrates the architecture:  
Encoder Part (Contracting path)
Upsampling2D
Decoder part (Expanding Path)
Skip Connection (Residual connection)

<img width="845" alt="image" src="https://github.com/yy7-f/Unet-Brain-Segmentation/assets/76237852/681fd494-4997-454d-8b35-3e4e31a1c0b3">

  
Prediction results:  
  
<img width="476" alt="image" src="https://github.com/yy7-f/Unet-Brain-Segmentation/assets/76237852/ac6c2016-b7f2-41f3-9496-06fef1b83c1d">

<img width="433" alt="image" src="https://github.com/yy7-f/Unet-Brain-Segmentation/assets/76237852/4780e045-e339-43a2-9d7e-f56edb4fd451">


  
Reference:  
Ronneberger, Olaf, Philipp Fischer, and Thomas Brox. "U-net: Convolutional networks for biomedical image segmentation." Medical Image Computing and Computer-Assisted Intervention–MICCAI 2015: 18th International Conference, Munich, Germany, October 5-9, 2015, Proceedings, Part III 18. Springer International Publishing, 2015.
