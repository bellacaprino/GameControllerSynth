# GameControllerSynth
 
 - Development Journal

## Hello gamers and welcome to Devnotes!

    This is basically a musical instrument for gamers, complete with FX, EQ, volume, pitch, and sample triggers.

    This patch is developed for a PS4 controller, and is designed to be used in tandem with the attached Ableton session - because of the midi mappings.

    A   user may use the shape buttons to switch between samplers, change pitch by rotating the controller, toggle FX with arrows, adjust EQ with the left stick, adjust panning with the right stick, adjust pitch and volume with the touch pad, and trigger samples with the triggers and bumpers.


# # Problem Log
    Regarding interpolation, this took me so long. I interpolated the toggling button for a very long time. I had to decide which buttons I wanted as toggles, and switches. Many iterations of buttons just weren't doing what I wanted them to do. (Lots of head banging ensured) I also kept having problems with the sends, so I ended up just copy and pasting into the patch itself. I also realized that during mapping, I had to unpatch and repatch anything with drift. I learned very quickly how to correctly process the data I was getting. I also learned how to use all of these Max objects, and that loading things is important :-)
    
    I also set a metronome on the pitch because I didn't like how it sounded when it was changing instantly. During this project I learned so much, and poured over documentation for hours. My knowledge of Ableton also improved dramatically. Simple put, LETS GOOOO!!!



# User Manual
    To initialize, open the Max patch and Ableton session at the same time. Users can replace the audio clips in sampler and in the triggering audio track. 

    The intended method of playing is to tilt the controller to change pitch, press buttons and have fun making weird sounds and triggering dumb samples.