# taptrap

Bill Ni, Starwarswii

### Installation + Run

Use any local http server to host the files in `public`, (such as [http-server](npmjs.com/package/http-server) from npm) then open up the site in your web browser.

### Instructions

 - Change recording length (in beats, 120 bpm) in input field below record button
 - Record using record button (there will be a 4 beat lead in)
 - Press the assign button and then a button from the 5x5 grid
   - That button now plays the sound when pressed
 - Assign keys by pressing the small tab at the bottom right corner of a button, and then pressing a key on your keyboard
 - Cycle audio output type with the tab at the bottom left corner of each button
   - Loop
     - Repeatedly plays sound
   - Cut
     - Sound plays, and if the button is triggered while sound is playing, the sound restarts
   - Overlap
     - Sound plays, and if the button is triggered while sound is playing, the sound starts over the original
