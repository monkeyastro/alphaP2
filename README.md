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

1. controller/evdev_controlthread.py : linux xbox controller interface code
2. contorller/ik.py                  : ik calculator. Simplified code for battery assembly. 
3. fastech/protocol.py               : fastech servo control api 
4. fastech/servo_state.py            : Joint state publisher
5. fastech/servolist.py              : kind of header for protocol
6. ros2/interface.py                 : default ros2 interface for the real robot
