# TimeSynthPresentation


	1. Add time synth plugin
	2. Add time synth clip: sounds > synthesis > time synth clip
	3. Add song to clip and change number of bars and beats
	4. Add TimeSynth Component to the blueprint you want it in.
	5. Set bpm of time synth component to the song
	6. On begin play, add a quantization event delegate. This will repeatedly run an event after the specified amount of beats/ bars have passed.
		a. The event attached to this can do things like move an object on beat, or only allow events on beat.
	7. On begin play, play the clip, specifying the clip you created.

