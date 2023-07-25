YOLOv4-tiny is the compressed version of YOLOv4 designed to train on machines that have less computing power. Its model weights are around 16 megabytes large, allowing it to train on 350 images in 1 hour when using a Tesla P100 GPU. YOLOv4-tiny has an inference speed of 3 ms on the Tesla P100, making it one of the fastest object detection models to exist.
Architecture
YOLOv4-Tiny utilizes a couple of different changes from the original YOLOv4 network to help it achieve these fast speeds. First and foremost, The number of convolutional layers in the CSP backbone are compressed with a total of 29 pretrained convolutional layers. Additionally, the number of YOLO layers has been reduced to two instead of three, with fewer anchor boxes for prediction.




