# Package E4_msgs
Set of messages to store Empatica data into ros2. These messages basically add a timestamp to a float, an int or a vector, so that we can store:

- TimedFloat.msg: IBI, GSR, Temperature, BVP, Battery level.
- TimedInt.msg: Status.
- TimedVector.msg: 3D acceleration.
