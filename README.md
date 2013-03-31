Hand-Passcode
=============

Uses the OpenCV library to read a sequence of images of a hand in different poses and positions, and determines if the correct sequence was given.

An assignment from a class called "Visual Interfaces", this program studies how to read images and interpret them as commands. The program can recognize a fist, flat closed hand, open hand, and a "knife chop". The correct passcode is an open hand in the center, followed by a fist in any of the four corners. The open hand is used as a blank - were this code modified to read real-time video data, it would be useful to have the computer recognize a wait gesture so the user can puase their activities without repercussions. The knife gesture, when first on the right half of the screen and then on the left, acts as a restart, letting the user start over completely.

This program uses OpenCV, which can be found at opencv.org
