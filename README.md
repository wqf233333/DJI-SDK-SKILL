# DJI-SDK-S(DK)K(nown)I(ssue)L(ist)L(ibrary)

FAQ of Onboard SDK , Guidance SDK and Manifold. Collected from Developers questions.

这是一个记录Onboard SDK讨论qq群（469284875）中关于DJI-SDK以及DJI相关产品的讨论内容的文档。

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

###Onboard SDK

- Why I cannot activate, why it failed open port.

  did you set a proper authority for the serial port?

- I can read nothing from the serial port

  check: enabled the API, same baudrate in Assistant/your program, if your USB-uart module works well
  
- What is encrypt error?

  it means you are trying to sending encode data while activation is forgotten or failed
  
- Could you add a feature to ... in the sample code?

  sample code is just a sample, you need to program by yourself
  
- How could I implement a function in order to ... ?

  Google/StackOverflow
  
- Why I code a function to ... but it didn't work?

  Google/StackOverflow

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
