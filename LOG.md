h1. PLAN

See what someone else is creating in VR.
Create things together.
Use Firebase.

How to send data?

1. Write to an array. Reciever always gets full array. Reciever runders full array.
   Inefficient. Easy.
2. Write updates. Overwrite the previous content.
   Recievers render whatever was posted in the update.
   Recievers take care of deleting their own old stuff.
3. Just send events. '
   Each reciever knows how to render events.
   Complictated.
4. Send each new trail segment using set. Reciever adds the new segment, and takes care of deleting the old segment. Pretty efficient!!

Doing 4..

- room1
  - user1
    - head position.
    - head rotation.
    - updates left.
    - updates right.


Animated things. Wormies.

h1. LOG

2021-11-19

Check that its ready for birthday with Tim.
Long enough trail.
There was a bug taht would cause buttons not to work.
Solution was to add the button detectors later with code at init time.
  document.getElementById('hand-left').setAttribute("button-listener","hand:left")
    document.getElementById('hand-right').setAttribute("button-listener","hand:right")
  
  Head!!!
  Hands!!!
  Turned off the opacity ramping as that seemed to screw up performance.
  Now you can add 'p'  parameter for how many segments the lines have.

  https://tinyurl.com/3745yzb4
  
  


2021-11-13

4. Send each new trail segment using set. Reciever adds the new segment, and takes care of deleting the old segment. Pretty efficient!!

Work on Firebase.
Next figure out how to do the users.
All in one bucket, or each gets their own?


2021-06-06

Recording and Playback is working now!



2021-06-05
Just need to get the playback working better.
It works the first time - but after that does not work correctly.
