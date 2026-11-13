LÖVEless is a fork of the *awesome* [LÖVE][site] framework which you can use to make 2D games in Lua. It's free, open-source, and works on Windows, macOS, Linux, Android, and iOS.

LÖVEless is focused on making LÖVE2d better to work with for a variety of things (including game development), but mainly windows applications.

This is made with personal use in mind, however I am making it public for that one person out there who will appreciate it.

Please star if you enjoy, it tells me you want to see more.

LÖVEless Changes
----------
Below are a list of all the changes present in LÖVEless, alongside planned changes. Sectioned into categories for viewing convenience. Note that something in one category can affect or have use case in another!

At some point I will probably make use of the GitHub wiki.


Windows Applications
----------

Prevents automatic window raising during window creation or recreation which can cause unwanted taskbar attention flashing. (e.g. when using love.window.updateMode).

Window Setting: .skiptaskbar - Window is not added to the taskbar.

Planned: Method to go borderless without recreating the window.

Planned: Minimize to tray / start in tray.

Documentation
----------

You can use the original LÖVE [wiki][wiki] for documentation on 99% of LÖVEless. 

Repository
----------

**Main** is the stable branch.
**Dev** is in development changes.
**Upstream** is for personal reference.

When LÖVE 12.0 comes out I *may* update this where applicable.

Building and Compilation
-----------

todo. For now check out the LÖVE [megasource][megasource].

Pretty much the same as the original, if you really want this right now I'm sure you can figure it out. 

Note: If you are building with CMake 4.0+ use $env:CMAKE_POLICY_VERSION_MINIMUM = "3.5"

Dependencies
------------

- SDL2
- OpenGL 2.1+ / OpenGL ES 2+
- OpenAL
- Lua / LuaJIT / LLVM-lua
- FreeType
- ModPlug
- mpg123
- Vorbisfile
- Theora

[site]: https://love2d.org
[wiki]: https://love2d.org/wiki
[megasource]: https://github.com/love2d/megasource

