# Compression-techniques-for-Semantic-Segmentation
Refer to the presentation for an overview of the whole project.
The "unet_training" file has the code for training unet model and quantizing it
The "unet_knowledge distillation" file has the code for training unet model with deeplabv3_resnet101 as teacher .
To run the models you would require Pascal Voc dataset which can be available by changing the torchvision.datasets.VOCSegmentation download to true
