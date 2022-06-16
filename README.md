# Lua Auproc C API 
<!-- ---------------------------------------------------------------------------------------- -->

The *Auproc C API* makes it possible to decouple [Lua] modules providing an audio processing 
engine from Lua modules providing realtime audio processor objects.

For further documentation see [auproc_capi.h](./auproc_capi.h).

<!-- ---------------------------------------------------------------------------------------- -->

### Implementations:

   * [ljack] - this Lua module provides an implemenation of the *Lua Auproc C API* to 
               be used with the [JACK Audio Connection Kit](https://jackaudio.org/).

   * [lrtaudio] - this Lua module provides an implemenation of the *Lua Auproc C API* to 
                  be used with [RtAudio](https://github.com/thestk/rtaudio).


### Invocations:
   
   * [auproc] - This package provides basic [Lua] audio processor objects to be used for 
                realtime audio and midi processing by using the *Lua Auproc C API*.

<!-- ---------------------------------------------------------------------------------------- -->

[Lua]:        https://www.lua.org

[ljack]:      https://github.com/osch/lua-ljack
[lrtaudio]:   https://github.com/osch/lua-lrtaudio
[auproc]:     https://github.com/osch/lua-auproc

<!-- ---------------------------------------------------------------------------------------- -->

## License 

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this
software, either in source code form or as a compiled binary, for any purpose,
commercial or non-commercial, and by any means.

<!-- ---------------------------------------------------------------------------------------- -->
