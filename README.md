# penguin2D
CSC418 Computer Graphics - Course Assignment 1

## Usage
Clone

```$ git clone https://github.com/username/software-project.git
...```

Make

```$ make
...```

Run

```$ penguin
...```

## Synopsis

The task is to design and render the articulated robot penguin using OpenGL. When the program is run, the robot should move (i.e., animate) in order to help test that the rendering is done correctly.

(a) Design the parts in terms of suitable generic shapes and deformations, and draw them using OpenGL.

(b) Design and implement suitable transformations that map each part’s local coordinate frame to the coordinate frame of its predecessor in the kinematic tree. Extend the GUI with additional spinners to control each of the 9 degrees of freedom (DOFs). Hint: The interactive DOF controls will be useful in debugging the transform hierarchy you build.

(c) Design and implement a set of functions that will control the animation, i.e., will control the state of each joint in each frame. You can use simple functions such as sinusoids to define the way in which parts move with respect to one another. Or, if you wish, you could specify a sequence of specific joint angles that the rendering will loop through. You can also use key-framing to specify a few key poses for the penguin (in terms of the joint angles) and linearly interpolate between them for smooth animation. Hint: You can use the GUI build for (b) to choose the set of key-frames or help you specify the values for the joint angles that produce the desired animation.

(d) Put it all together to generate your animation, by drawing each part in turn as you descend the kinematic tree (once per frame). Use the OpenGL transformation stack to control relative transformations between parts, the world and the display device. It is not necessary to write code that could be used to render arbitrary articulated objects, thereby requiring that your code can traverse any kinematic tree. To keep things simple, you may hardcode the sequence of parts that are drawn.

(e) Be sure to also draw the small circles which depict the locations of the rotary joints.

+ Written report for all functionalities above

## License

The MIT License (MIT)

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
