# DJI-SDK-S(DK)K(nown)I(ssue)L(ist)L(ibrary)

FAQ of Onboard SDK , Guidance SDK and Manifold. Collected from Developers questions.

这是一个记录Onboard SDK讨论qq群（469284875）中关于DJI-SDK以及DJI相关产品的讨论内容的文档。

Please follow the [guideline](https://github.com/wqf233333/DJI-SDK-SKILL/wiki/Format-Guideline) if you want to contribute

We also provide a [dynamic search tool](http://dji-brainhole.github.io/hippophae/index.html) of this issue list, all issues are synchonized from this readme file.

For new issues please submit them in Github Issue of this repository.

###ROS

- What is ROS and how to work with it?

  http://wiki.ros.org/

- How could I compile and run the pkg?

  http://wiki.ros.org/catkin/Tutorials

- I compiled but cannot find pkg when roslaunch or rosrun

  usually it means you forget `source devel/setup.bash`

###Zenmuse X3

- Can X3 installed upside down?

  Contact @lanyusea if you have this kind of purpose, there is a special firmware for it.

- How could I read the video buffer from X3 if I have no manifold

  Sorry I cannot tell you.

- How can I get the video of X3 for image processing?

  There are two ways to achive it: 1.using Manifold as onboard processor 2.using HDMI output of RC remote controller

###Onboard SDK

- Why I cannot activate, why it failed open port.

  did you set a proper authority for the serial port?

- I can read nothing from the serial port

  check: enabled the API, same baudrate in Assistant/your program, if your USB-uart module works well

- What is encrypt error?

  it means you are trying to sending encode data while activation is forgotten or failed.

- What is the default taking-off altitude and how to modify it?

  the drone will exit the taking off logic after reaching 1.2m and it is a fixed height which cannot be modified

- How to read the C1/C2 value of RC in Onboard SDK?

  no you cannot, the only channel values can be read from broadcast are roll/pitch/yaw/throttle/gear/mode

- Could you add a feature to ... in the sample code?

  sample code is just a sample, you need to program by yourself

- How could I implement a function in order to ... ?

  Google/StackOverflow

- Why I code a function to ... but it didn't work?

  Google/StackOverflow
  
- What is the meaning of parameter in Onboard-SDK-ROS/dji_sdk_demo/src/client.cpp/drone->attitude_control(0x40, 0, 0, 0, 0)? 
   


- How to understand the "HORI_POS" in Appendix.md?



- When I run the demo in Onboard-SDK-ROS/dji_sdk_web_groundstation/,I click the "Start-Planning",it warns "home location not Recorded",any idea on how to resolve this problem?



###Gudiance SDK

- Can I use Guidance for SLAM?

  Yes.

###Manifold

- Where can I find resources of Manifold?

  http://forum.dev.dji.com/thread-32204-1-1.html http://forum.dev.dji.com/thread-32205-1-1.html http://forum.dev.dji.com/thread-32206-1-1.html http://forum.dev.dji.com/thread-32207-1-1.html

- What is the serial device name?

  /dev/ttyTHS1

- Where can I get the  image file of Manifold?

  https://dl.djicdn.com/downloads/manifold/manifold_image_v1.0.tar.gz

###Mobile SDK

![](http://3.bp.blogspot.com/-Z5vydmzLOuI/VFNTYpbOmlI/AAAAAAAAAEM/VO3_IlSqnqI/s1600/94eb289f247f6e711a9975bed6783d1db4a15af4a9f2b7cd8f1a560a3bfb540a.jpg)

###Others

- You guys are awesome!

  Thank you!
