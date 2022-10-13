Here is a public collection of my Unreal 4/5 notes.

''LogAkAudio spam''
If you want to suppress it, the command "Log LogAkAudio None" will get rid of it for a session (and everything else from the LogAkAudio channel)
In case you want it gone forevermore: add a [Core.Log] section into DefaultEngine.ini, with a line "LogAkAudio=None" in there.
BaseEngine.ini has an example, line 957
