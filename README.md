# NSTNet-Neural_stryle_transfer
Blending of two image content using the customized GAN


Used VGG16, which is pre-trained on the ImageNet dataset and modified the last layers of the VGG16. The training VGG-16
generates features arrays of the reference picture and style image since the top (i.e. classification) module is not included. The
model is trained for 310 epochs, with a content loss weight value of 1.9 and a style loss weight value of 1500000. Below
images describes the checkpoints of the epochs at constant interval.




<img width = "256" alt = "NSTNet" src = "https://drive.google.com/file/d/1mJ7AT5UM_nYx65JQnfaWZRvy60ZNxCJJ/view?usp=sharing">
