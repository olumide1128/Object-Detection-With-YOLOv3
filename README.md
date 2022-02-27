# Object-Detection-With-YOLOv3
This is an Object Detection script created using the YOLOv3 CNN model in python which can detect multiple objects at a time in an image.

# Download Yolo.weights for Classification
- After cloning this repo, you want to download the yolo.weight file from here >> https://pjreddie.com/media/files/yolov3.weights
- Place this download file in the "yolo-coco" folder in the cloned repo.

# Instructions
- Place any image you want to detect in the images folder in the project.
- To run the script, you want to go to the root directory and type this >> python yolo.py --image {{image_name}} --yolo {{yolo_path}}
- Where the {{image_name}} is the name of your image and {{yolo_path}} is the path to yolo-coco dir, which is simpply "yolo-coco"

# Example
- python yolo.py --image dog.jpg --yolo yolo-coco

![Image showing Object Detections](https://github.com/olumide1128/Object-Detection-With-YOLOv3/blob/master/Screenshots/detections1.png)


Cheers!!
