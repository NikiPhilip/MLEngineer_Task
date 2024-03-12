
1.	Data Collection: The necessary libraries are imported.The images of cricket bats were taken from roboflow. 
2.	Annotation: Annotated the images to mark the coordinates of the cricket bats from roboflow.
3.	Train-Test Split: Split the dataset into training and testing sets and creating respective .txt files containing the paths of the images.
4.	Training YOLO model: Training a YOLO v8 model on the provided cricket dataset using the yolo command.
5.	Object Detection: Performing object detection on an image using the trained YOLO model.
6.	Displaying Bounding Boxes: Displaying the detected objects in the image along with their bounding boxes and printing their coordinates.
7.	Corner Detection: Performing corner detection within the bounding boxes of the detected objects.
8.	Displaying Corners: Displaying the image with marked corners within the bounding boxes.

Challenges faced
1.Sufficient images of cricket bats were not available and only a certain number of images were taken and the model was trained with.
2.Annotating the Corners: Accurately annotating the positions of the four corners of the cricket bat in each image was a bit difficult and prone to errors and it was possible to detect only 2 corners of the cricket bat.

