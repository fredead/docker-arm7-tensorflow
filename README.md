Tensorflow 2.1.0 for rasberry pi 4 (arm7) docker container

```
fredead@raspberrypi:~/learn $ docker run -it fredead/tensorflow-arm7 bash
root@783e1df5f585:/# python3
Python 3.7.12 (default, Jan 13 2022, 21:15:48)
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow
>>> tensorflow.__version__
'2.1.0'
```

I wanted to try out tesnor flow. So I upgrade the OS to the latest as it was quite old. It was then I found tensorflow was not support but was in the previous.
Long story short after trying a couple of other things I ended up building a docker container. A cloud server would have been easier or possibly cross compiling . 

useful webpage

https://qengineering.eu/install-tensorflow-2.1.0-on-raspberry-pi-4.html

The bazel build did not compile on my machine for unkown reasons and caused the pi to crash. I have no terminal attached so was unable to find teh proble
