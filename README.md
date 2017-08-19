Self-Driving Car
================

Acquire The Dataset
-------------------

### Driving info

Requirements: Steering wheel angle, pedals pression

Get OBD info.

Hardware:

- PiCAN2 43€
  http://skpang.co.uk/catalog/pican2-canbus-board-for-raspberry-pi-23-p-1475.html
- Raspberry PI 3, 55€
  https://www.amazon.fr/Raspberry-Pi-Official-Desktop-Starter/dp/B01CI5879A/ref=sr_1_3?s=computers&ie=UTF8&qid=1503146205&sr=1-3&keywords=raspberry%2Bpi%2B3&th=1
- db9 <=> obd cable 10€
  https://www.amazon.fr/Ake-16PIN-Serial-Diagnostic-Connection/dp/B01J9QOC22/ref=sr_1_cc_1?s=aps&ie=UTF8&qid=1503146353&sr=1-1-catcorr&keywords=db9+obd

Total: 108€

Software: Python-CAN / SocketCAN

https://python-can.readthedocs.io/en/latest/

Rpi powered by laptop. SSH via wifi or Ethernet.

### Video

Requirement: wide video, with sides and back mirror, and no steering wheel.
Gonna be complicated. Read SOTA about single cameras autopilots. Or, first
test: lane assistance.

Fisheye on smartphone? Test it.

3D printed mount? Try it. Who could print?

Learning
--------

Tensorflow + AWS

Driving
-------

Have a motor rotating the steering wheel and a spring for the pedals. How to
find enough power? How?

~~I could also directly use CAN but it needs insights from DACIA.~~
Transmission is mechanical. I have no other choice but to turn the steering
wheel.

Computing: Laptop in the car? High-end smartphone?

Resources
==========

* https://github.com/jaredthecoder/awesome-vehicle-security
* https://www.reddit.com/r/CarHacking/
* https://github.com/P1kachu/talking-with-cars
  PyCAN examples
* http://opengarages.org/handbook/ebook/#calibre_link-262

