# cgPiano
## Computer key-board piano, simplified memorizing: one-finger plays one-number-name's low middle high notes
### cgPiano035.zip is the newest. If you do not play chords, cgPiano027.zip might be esaier.
- This soft piano (CG piano) is designed and programmed by Dr.ChenGuang, under the MIT License.
- It is very easy to memorize the keys, because one finger plays low mid high notes of the same number:
- left-little-finger controls keys Z, A, Q for low 1, mid 1, high 1
- left-ring-finger controls keys X, S, W for low 2, mid 2, high 2
- left-mid-finger controls keys C, D, E for low 3, mid 3, high 3
- left-index-finger controls keys V, F, R for low 4, mid 4, high 4

- right-index-finger controls keys M, J, U for low 5, mid 5, high 5
- ... ...
- Same as and easier than Standard English Typing Technique.

- You can choose to make the sound continue after releasing a key until you play another note or press the space-bar.
- You can also choose to make the sound stop as soon as you release a key.

- Tone.js is the function-library for music downloaded from
- https://cdnjs.cloudflare.com/ajax/libs/tone/14.8.39/Tone.js

-  This project uses Tone.js, which is licensed under the MIT License.
- Tone.js Copyright (c) 2014-2020, Yotam Mann
- License: https://github.com/Tonejs/Tone.js/blob/dev/LICENSE.md

## From cgKeyBoardPiano026.html on:
- Change-pitch function is added: click in the input-box and rotate mouse wheel to set how-many semitones. 
- When a key is pressed, if it has note, its note will play for a long time, until the next key is pressed to play another note or space-bar pressed to stop. 
- It also needs Tone.js, just like cgKeyBoardPiano025

## From cgPiano027 on:
- Shift+key plays 1 semitone higher. Just like the black keys in piano. 
- Change pitch: rotate mouse-wheel or left right up down arrow-keys. 
- Change pitch is displayed as both n semitones and letters.

## from cgPiano028 on:
- Allows pressing 2 or 3 keys at the same time. Of course, pressing one by one is also OK.

## from cgPiano029 on:
- All the keys corresponding note are shown in web-page, keeping the order in key-board.
- When a key is pressed, the back-ground becomes black.

## from cgPiano030 on:
- g,h,t,y,b,n are made into chord-keys.
- Pressing a note key, then press any chord-key, 
- A lower chord-note will accompany the main note.
- Press the chord-key again and again, will change into the other chrod-notes .

## from cgPiano031 on:
- Added check-box to choose when multiple keys pressed, play chord or not. 
- Introduced name-space-objects. 

## from cgPiano032 on:
- name-space-object defined dom, thus can be an easy frame-wrok of JavaScript

## from cgPiano034 on:
- Name-space-object based POP like OOP can generate new objects. 
- This technique is used here to generate combined-doms here, thus is the prototype of a JavaScript frame-work, like React and VUE. 
- Space-bar is used for auto-chord, Enter and the near-by keys: ' ] \  for stop. 

## from cgPiano035 on:
- Added keys G, H, SpaceBar to the key-board in GUI
- Made the keys equal in size. 
