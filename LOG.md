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

2 sounds good.

- room1
  - user1
    - head position.
    - head rotation.
    - updates left.
    - updates right.

h1. LOG

2021-06-06

Recording and Playback is working now!

2021-06-05
Just need to get the playback working better.
It works the first time - but after that does not work correctly.
