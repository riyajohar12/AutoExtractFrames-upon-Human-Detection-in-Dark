# AutoExtractFrames-upon-Human-Detection-in-Dark
This is a deep learning based project, it addresses very important aspect of various application. Face recognition, or human activity detection as these tasks need good environment. This project address the scenario when environment is not as desired like night CCTV camera. This project focused mainly on CCTV footage video for reference.

It downloads all the frames when human is getting detected in a zip file, and then later it can be used for various tasks like face recognition etc., using YOLOv3

Run this code first (if running for the first time)

!wget https://pjreddie.com/media/files/yolov3.weights -O yolov3.weights

!wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg -O yolov3.cfg

!wget https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names -O coco.names
