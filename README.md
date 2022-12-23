# Loopy
Loopy is a quantized looper program designed for Orac. It is capable of storing two sets of loops as switchable A and B section, stuttering the loop at various rhythmic intervals, variable speed back playback, on board delay, and more.

# Recording a phrase

Upon loading Loopy into a new module slot, you are greeted with the Recording screen. Before recording your loops, there are some processes that need to be functioning correctly to ensure proper playback. With some new improvements to Loopy, these should be taken care of automatically. The first thing you should do is determine how long you want your loop lengths to be and confirm them with with the high F# key. By default, it records 4 bars in 4/4.

You'll notice that there is a number that is counting at the bottom of the screen. That number corresponds to the internal Loopy clock. If you do not see this number, you have to use either a modified Multicycle I will upload or Transport by @electrafa as your clock module. Whenever it strikes 1 is when all the armed actions start so it is important to make sure this is lined up with the rest of your patch.

Because I have now tied this functionality into these two clock modules, it should automatically align. If it ever falls out of time or is not synced, tap the high G# key along with either some drums you have playing or turn on the metronome in your clock module and line up the 1 with the loudest, most prominent click.
When the clock is counting along properly, you are ready to start recording. To start the arming process, click either the aux button, high C, MIDI CC or use a foot switch. Recording will start and will list what array is currently being recorded to when the next 1 is reached. Recording will automatically stop and begin looping upon completion. You can stop looping with the high D# and restart it with the high C#. Starting and stopping are quantized as well.

# Clearing a messed up phrase

If you made a mistake in your recording and want to start over, click the high F to clear the A array or the high G for the B array. You can then quickly rearm to start recording again.

# Switching A/B sections

There are two ways to access the other array. When your A array is playing and you want to start recording into the B array immediately after switching, click the high B. Recording of the B section will automatically stop. You can switch back to the previous  section without recording with the high A.

# Using the delay

There is a simple onboard delay which can be tempo synced on the first page. There are more controls on the second page listed as Volumes. You can control the delay feedback and time on this page. There are controls for the master volume and delay volume on a different page.

# Controlling the volume

I like to leave the Input and Recycle volumes at about 75% to get slight lowering in volume as more layers are added. If you mess up and accidentally record too low, you can find the master volume on a different page. There is also a momentary kill switch on the low C for quick rhythmic muting.

# Stuttering

There is now note repeating allowing for you to stutter your loop at different rhythmic intervals. The keys from low F to low A# are dedicated to stuttering at different rates. F is 1/2 notes, G is 1/4 notes, A is 1/8 notes and B is 1/16 notes. F# triggers 1/4 triplets, G# is 1/8 triplets, and A# is 1/16 triplets or 1/24 note.

# Reversing

There is also now variable playback speed but quick reversing and playing forward of the playback material can be triggered with the low E.

# Playback speed

There is now variable playback speed. This can be used to manually reverse or play forward the sample. The low C# will move downwards by 50% and the low D# will increment by 50%. By default these move by intervals of 50% but pressing the low D will make them adjust in increments of 25%.

# Array copying as undo

Array copying is a new feature that can be used to duplicate one array into the other to make some changes to the loop but keeping previous elements or it can be used for undoing mistakes. If you are building up a loop on the A array and want to ensure the current loop does not get lost, you can copy the A array into the B array with the high D. You should see A -> B on the bottom line. After that you can start recording again as normal. If you messed up and want to have the old loop that you stored in the B array, click the high E. You should see A <- B on the bottom line.

# MIDI mapping

You can map functions of Loopy to outside MIDI devices to trigger it even when it is not your active module. The CCs that are mapped to the functions can be changed via the MIDI screens. I personally use a MIDI Fighter Twister to trigger these functions by pressing on the knobs. I have also set up two of the CCs for the Recording Indicator light and Clock Indicator which will display what number the clock is on using the LEDs and when it is recording by lighting all of the LEDs up.

# Sample loading

Outside samples can now be imported for use in Loopy. Go to the second to last page labeled Samples. There are multiple directories that house samples that can be chosen. They draw on the same directories that OracLoops uses. Before you choose a sample, select your array that you want the sample to overwrite into. This is determined by if Sample Array is set to 0 for A or 1 for B. When that has been set, select your directory and sample and it should load automatically. The length of the sample is determined by the A and B length parameters on the main page.

# Alternative time signatures

Loopy assumes a 4/4 time signature by default but it can now be used effectively with alternate time signatures. Go to your clock module and set your time signature there. After that has been set, you will now notice Loopy counts to the number you specified. Set your A and B lengths accordingly to your chosen time signature and you should now be able to use Loopy with varying time signatures.

# Writing loops to disk

Loopy now has the ability to write and record your loops to disk for use in other programs like Samplement and OracLoops. You can also take them off your Organelle for further processing in a DAW. To arm the writing process, click the high A#. The writing process is quantized similar to the start, stop, arm recording, etc. When you begin recording, it will display a count in the bottom line of the screen listing the name of the file and how long it has been recording. Click the high A# again to stop the writing process on the next 1. All the samples get stored in the media/captures directory.
