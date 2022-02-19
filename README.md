# POI-Detection-of-High-Rise-Buildings-Using-Remote-Sensing-Images-Dataset
Remote sensing images and labels of the building roofs and the whole building shapes.

The data were obtained from remote sensing images of urban areas of Shenzhen, China in Google Earth.
In this study, we collected 108 remote sensing images sized 1,024x1,024 pixels. For every image, we manually outlined all the building roofs and the whole building shapes in it, respectively. In this study, remote sensing images were labelled by the VGG Image Annotator (VIA) tool. For both the building roofs and the whole building shapes, annotated images were first saved as the JavaScript Object Notation (JSON) format, and then were transferred into binary images with only black and white colors. Finally, every remote sensing image was split into 4 images with the size of 512x512, and the same operation was also performed on the binary images.
