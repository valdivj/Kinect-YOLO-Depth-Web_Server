# Kinect-YOLO-Depth-Web_Server
Of course I could not have accomplished this with out the hard work of others.

You have to have darkfloww YOLOv2 set up onn youre PC for these programs to work.
Check out the Darkflow web page:https://pjreddie.com/darknet/yolov2/
Real-time object detection and classification. Paper: version 1, version 2.

Read more about YOLO (in darknet) and download weight files here. In case the weight file cannot be found, I uploaded some of mine here, which include yolo-full and yolo-tiny of v1.0, tiny-yolo-v1.1 of v1.1 and yolo, tiny-yolo-voc of v2.

Also thanks to:
Flask Video Streaming Revisited
Posted by Miguel Grinberg under Flask, Python, Programming, Video

By following Miguel's lesson I was able to incorperate flask into my Kinect Yolo projects.

1. app.py: This is the one to run. It calls Kinect.py to run and runs it in a web server.
The webb sever can be called by running xxx.xxx.xxx.xxx:5000 (youre PC's I.P address)
in any web browser.

2. webcam.py: this is just a simple opencv webcam app.



