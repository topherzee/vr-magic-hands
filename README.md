# vr-magic-hands

Playing with creating and casting magic with hand motions. With controllers for now.

WebVR project.

Only tested on Oculus Quest 1.

Surf to this URL in your Browser in your VR device.

# BENDING
Use the trigger to bend teh balls.
Use the grip button to Throw them.


## Start

To Start
http-server -S -C cert.pem

## LOG

Working on steering water once it is launched.

## Did this:

Refacgtoring- 
Left ball - thickness is messed up.
Cannot throw as normal.
Hide the tips - make them invisible in BENDING MODE.

Add an indication of where the control point is, when thrown.

You can add ?playing=1 to get it to play the recording.
You can set a global to RECORDING in order to record a new track - it can then be copy/pasted from the DevTools Local Storage.


## TODO

Initialize the system better!

### Getting water

IN PROGRESS! TIDY UP AND CHANGE COLOR.
Somehow it starts automatically but it should not.

Move hand below 0.5 to activate.
Move hand above 1.0 to start pull.
Move hand below 0.5 to reactivate
gCollectState[H]; NONE, STARTED , PULLING, DONE
gCollectEnergy 0 to 1.0?

Get the cone to point to slowly stretch up to the hand.
Put the cone in a group, so we can rotate it.


Hide all the other stuff!

Make water go boom.
Sommon the water back.
Start with a small water - energize it by spinning it.
Add texture /shader to water surface.

Shaders:
https://codepen.io/topherzee/pen/WNpavLg

https://codepen.io/KiranWells/pen/gObrXXm

Wild:https://glitch.com/edit/#!/aframe-displacement-shader?path=shaders%2Fvertex.glsl%3A1%3A0

Amazing water surface: https://www.shadertoy.com/view/4dBcRD

Interesting - but not really it: https://github.com/SamsungInternet/a-frame-components/blob/v0.0.1/dist/webgl-ocean-shader.js

Environment map component: https://github.com/msfeldstein/aframe-environment-map-component
