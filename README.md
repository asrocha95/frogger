# Frogger (GoT)

This a simple Frogger like game developed as an exercise to coding and software development.
Using the Allegro library and basic concepts of the C programing language, 
this project was developed as an introduction me to the many aspects of programing. 
It contains some simple concepts such as file management, frame refresh rate, input keyboard commands, and others.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To run the game in your local machine, you will need only a C compiler and the [Allegro](https://www.allegro.cc) 
library installed in your computer.

Instructions to install the Allegro library can be found at: [https://www.allegro.cc](https://www.allegro.cc) 

### Compiling and running the game

After the *Allegro* library is installed, clone the repository to your local machine. Open the *Terminal* (MacOS)
or the *Command Prompt* (Windows) at the cloned folder and run the following command:

```
gcc -o frogger main.c -lallegro -lallegro_main -lallegro_image -lallegro_font -lallegro_ttf -lallegro_primitives -lallegro_audio -lallegro_acodec
```

This should generate a compiled file of your game with the name ``frogger``.
Now simply run the compiled game by running the following command in the command line.

For MacOS:
```
./frogger
```

and for Windows:
```
frogger
```

It should be noted that, altough these steps should work on any platform, this program was tested on MacOS only.


## Authors

* **Arthur de Senna Rocha** - [asrocha95](https://github.com/asrocha95)