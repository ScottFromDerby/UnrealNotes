# UnrealNotes

Here is a public collection of my Unreal 4/5 notes.

## Links
[ari.games](https://flassari.notion.site/Ari-s-Unreal-Engine-Notes-1a75e43f4014464984d4fae0617e5cef)

## LogAkAudio spam
If you want to suppress it, the command "Log LogAkAudio None" will get rid of it for a session (and everything else from the LogAkAudio channel)

In case you want it gone forevermore: add a [Core.Log] section into DefaultEngine.ini, with a line "LogAkAudio=None" in there.

BaseEngine.ini has an example, line 957

![ScottAvatar](https://media.retroachievements.org/UserPic/Scott.png)
![Default](https://media.retroachievements.org/Images/000001.png)


## C++ General stuff

### Alternative Function Syntax

auto music_create(int seed)->std::shared_ptr<music_t>;

is equal to

std::shared_ptr<music_t> music_create(int seed);

https://blog.petrzemek.net/2017/01/17/pros-and-cons-of-alternative-function-syntax-in-cpp/
