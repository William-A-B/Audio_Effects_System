# Audio Effects System
This project idea has been around for over 4 years, originally thought of as an extension to one of my first electronics projects a Violin Tuner, and since then it's always been in the back of my mind to create some sort of effects pedal or sound system which allows various audio effects to be applied to an audio signal.
This project is therefore the reaslisation of that original idea.

As you are reading this, I am still in the early stages of the project planning and I am currently researching viable methods for implementation. My current route will involve utilising the VAM (Versatile Amplifier Module) which was a part of the 1st year Analogue Engineering module. This will provide a very basic soundcard and audio interface to get started with the project.

Utilisng the VAM along with the raspberry pi will provide all the key aspects needed hopefully, and I am looking at starting out with some simple python to interface with the GPIO pins and apply some simple audio effects using a FFT (Fast Fourier Transfrom) library or similar DSP library.

At a later stage, I may explore rewriting this project in C, and utilising more high power libraries which will provide more control and LOD to the project.
