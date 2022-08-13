# KontrolScape
 Simplified Interface for controlling d&b Soundscape

I started this project in an attempt to abstract away some of the complexity and robustness of R1 when using it for Soundscape control.
Changing views depending on whether you wanted to control reverb send, object position, or some other parameter, seemed cumbersome and slow, so I decided to make a controller that put all the parameters in one interface, and made the desired sound object selectable instead.

We also required a great deal of QLab programming, frequently updating position and other parameters during a 2.5 hour musical, so I incorporated the ability to automatically write cues into a QLab session. This dramatically decreased our programming time. This was a very complex show in sound world, but we slipped under the radar, and no one really noticed just how much was happening at our tech table.

This was my first Max project, and there is still much to be desired, but I hope that in this early state, it will still serve others well. There are a few things you may have to do to get it up to spec.

1. Under Options>File Preferences, click the \+\ in the bottom left-hand corner to add a path. Here you can navigate to the Image Assets folder, which is where the pictures of the concert halls are kept.
2. Unlock, select the pictslider object (the big rectangle in the middle), navigate to the inspector/Image, and choose your background image. This can be a groundplan of the stage. You may have to rescale this middle section; I want to make this process more automated, but this is where it is for now.

The documentation should explain the rest.
