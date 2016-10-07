## Synopsis

Install Tips for Eddie Robotics Package


## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Installing in a Vanilla Ubuntu 12.04 image on VMWare

1. 

Dependencies:
1. kd
 1.rosdep install kdl
 2. rosmake kdl
2. app_manager
      1. git clone https://github.com/pr2/app_manager.git
      2. sudo easy_install app_manager
3. joy
      1. sudo apt-get install ros-groovy-joystick-drivers
4. openni_camera: http://wiki.ros.org/openni_camera
      1. sudo apt-get install ros-groovy-openni-camera
      2. sudo apt-get install ros-groovy-openni-launch  

5. Complete eddibot install
      rosdep install eddiebot
6. sudo chmod 666 /dev/ttyUSB0


## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
