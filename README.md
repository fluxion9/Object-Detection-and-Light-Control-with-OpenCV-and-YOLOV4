# Object-Detection-and-Light-Control-with-OpenCV

OpenCV `dnn` module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow. 

When it comes to object detection, popular detection frameworks are
 * YOLO
 * SSD
 * Faster R-CNN
 
 Support for running YOLO/DarkNet has been added to OpenCV dnn module recently. 
 
 ## Dependencies
  * opencv
  * numpy
  
`pip install numpy opencv-python`

 ## YOLO (You Only Look Once)
 
 Download the pre-trained YOLO v3 weights file from this [link](https://pjreddie.com/media/files/yolov3.weights) and place it in the current directory or you can directly download to the current directory in terminal using
 
 `$ wget https://pjreddie.com/media/files/yolov3.weights`

 ## OR

 `wget https://pjreddie.com/media/files/yolov3-tiny.weights`

 For Constrained Environments
 
 Provided all the files are in the current directory, below command will apply object detection on the input image `group.jpg`.
 
 `$ python3 yolo_opencv.py --image group.jpg`
 
 
 **Command format** 
 
 `$ python3 yolo_opencv.py --image /path/to/input/image`
 
 
 ### Sample Output :
 ![output](object-detection.jpg)
 
