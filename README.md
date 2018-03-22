# rpi-matrix-acn-e1-31
Controlling of 32x32 or 16x32 RGB LED displays using Raspberry Pi rpi-rgb-led-matrix with sACN E1.31

sACN E1.31 is a protocol for controlling lights over a network. Jinx
controls LEDs on one or more sACN E1.31 nodes. An sACN E1.31 node drives the
LEDs. In this example, Jinx runs on a laptop and controls a Pi with
a rpi-rgb-led-matrix RGB LED displays using Raspberry Pi. The Pi is the sACN E1.31 node.
A RGB LED displays 32x32 / 32x16 / 64x64 or higher and an add-on board connected for a Raspberry Pi+/3

# rpi-matrix-acn-e1-31
Controlling up to 64x64 and more RGB LED Matrix Display with sACN E1.31 Protocol

E1.31 is not proper implementet jet.

## Preliminary

RGB LED displays rpi-rgb-led-matrix Program for Raspberry Pi must be installed and working on the Pi
supplied Python software. Make sure this works before graduating to sACN E1.31.

https://github.com/hzeller/rpi-rgb-led-matrix

There is also a Art-Net implementation on https://github.com/darknessii/rpi-matrix-acn-e1-31 

## Install libraries on the Pi

Do this only once to install the Python twisted libraries.

```
sudo apt-get install python-twisted
```

## Run sACN E1.31 server rpi-matrix-acn-e1-31 on the Pi
The following command runs the sACN E1.31 server turning the Pi into an sACN E1.31 node. 
Many programs can send LED values to an sACN E1.31 node. Glediator and Jinx is such a
program.

```
sudo python rpi-matrix-acn-e1-31.py
```


## NOT working
* Multicast Support

## TO DO
* a lot... give some input

## Jinx!

Jinx! – LED Matrix Control

Jinx!, is a free available software for controlling LED matrices.

* http://www.live-leds.de/

## Glediator

See the Glediator download page to download and install Glediator.

* http://www.solderlab.de/index.php/software/glediator

## xLights

xLights is a free and open source program that enables you to design, create
and play amazing lighting displays through the use of DMX controllers,
E1.31 Ethernet controllers and more.

* https://xlights.org/




