# How to play

Run alien_invasion.py to play

# Install requirements for mac

`$ brew install hg sdl sdl_image sdl_ttf`

`$ pip3 install --user hg+http://bitbucket.org/pygame/pygame`

# Installing Pygame on Linux

If you’re using Python 2.7, install Pygame using the package manager. Open a terminal window and run the following command, which will download and install Pygame onto your system:

`$ sudo apt-get install python-pygame`

Test your installation in a terminal session by entering the following:

```$ python
>>> import pygame
>>>```

If no output appears, Python has imported Pygame and you’re ready to move on to “Starting the Game Project” on page 240.

If you’re running Python 3, two steps are required: installing the libraries Pygame depends on, and downloading and installing Pygame.

Enter the following to install the libraries Pygame needs. (If you use a command such as python3.5 on your system, replace python3-dev with python3.5-dev.)

`$ sudo apt-get install python3-dev mercurial`
`$ sudo apt-get install libsdl-image1.2-dev libsdl2-dev libsdl-ttf2.0-dev`

This will install the libraries needed to run Alien Invasion successfully. If you want to enable some more advanced functionality in Pygame, such as the ability to add sounds, you can also add the following libraries:

`$ sudo apt-get install libsdl-mixer1.2-dev libportmidi-dev`
`$ sudo apt-get install libswscale-dev libsmpeg-dev libavformat-dev libavcodec-dev`
`$ sudo apt-get install python-numpy`

Now install Pygame by entering the following (use pip3 if that’s appropriate for your system):

`$ pip install --user hg+http://bitbucket.org/pygame/pygame`

The output will pause for a moment after informing you which libraries Pygame found. Press ENTER, even though some libraries are missing. You should see a message stating that Pygame installed successfully.

To confirm the installation, run a Python terminal session and try to import Pygame by entering the following:

```$ python3
>>> import pygame
>>>```

