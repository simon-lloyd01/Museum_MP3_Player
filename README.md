This MP3 player was designed to play audio effects or commentary in a museum’s  exhibition rooms, hopefully bringing the exhibits to life. Our museum is small and niche, opening only one weekend a month, so won’t get a lot of visitors. The players needed to be flexible, quick to deploy and as cheap as chips. So they were designed using Arduino Uno’s or Nano’s with simple MP3-TF-16P (DFPlayer Mini compatible) MP3 player modules and the most basic HC-SR501 PIR motion sensors. 

It works in several modes: single clip playing and pausing a while in a loop, playing multiple clips in sequence or randomly. Playing clip or clips when a visitor enters a room. There is always a pause adjustable from seconds to minutes – just to stop us being driven insane by hearing the same clips all the time. 

Different rooms require different modes of player and different pauses. 
When powered on it reads the mode, delay and clip volume then starts playing at once to check it’s working. Then continues in the play/pause loop or pauses and waits for a trigger. The unit has a passive infrared motion sensor to detect visitors entering one of the exhibit rooms. It has an external switch to swap between loop play mode and the PIR triggered by visitors mode.

It can use a small speaker connected directly to a power amp on the MP3 module or use the L+R output into a separate amp and speakers. The later gives the option of stereo sound or if you put different audio on each leg you have dual channel synchronous effects.

I find myself changing modes often while working out which mode works best for different areas. So I keep uploading different settings. To avoid much of my recent pain make sure if you buy cheap Arduino clones that you buy ones with Boot Loaders. It's wasted so much time having to use an external programmer instead of just using the Arduino IDE upload button. 

I wanted the finished units to look neat, so there are also a couple of very simple 3D printable cases based on modified files from thingiverse.com. These use Uno boards and not the smaller Nano, as it turned out neater to fit a proto board on top of the Uno to mount the MP3 module. in the same footprint.
