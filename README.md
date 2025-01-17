# alphaP2 - IndVision

* Requirements *

1. full version package is developed under collab. python 3.

* Required packages *

1. numpy : math lib
2. matplotlib : plot tools
3. cv2 : opencv2, analyzing pictures, adjusting properly on collab environment
4. requests : https protocol api (ros2 msgs via ros2-websocket bridge)
5. torchvision : dataset(image) settings, transform for image pre-processing and tensor for learning
6. image : PIL, image load

* File discriptions *

1. image_print.py  : printing original image
2. canny_trial.py  : image with canny process applied to detect edge
3. sobel_trial.py  : image sliced with sobel process apllied 
4. slicing_canny.py  : image sliced with canny and gaussian blur applied
5. holedetect_withloc.py  : detect hole with houghcircle, points the position of it
6. ai_adv_holedetct.py(unfinished part yet) : ai model trained with given pictures(about 400 data)
