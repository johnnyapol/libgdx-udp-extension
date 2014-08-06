libgdx-udp-extension
====================

UPDATE: SUBMIT YOUR COMMENTS HERE!: https://github.com/libgdx/libgdx/pull/2209
===============================================================================

An experimental UDP extension for the LibGDX library aimed at doing its job with as little allocations as possible. It can easily be ported to other libraries. 

Goals
====================
The goals of this project is to create a simple UDP library that abstracts as much as possible away from the networking part making the developer's life easier and limiting the requirement of the knowledge in the area. It makes working with UDP a lot like TCP in the sense. This also was designed in mind to limit allocations to conserve memory. 

Dependencies 
====================
The current dependencies are LibGDX. This can be very easily be ported to other libraries or made standalone. If I get enough requests I'll put up a version that doesn't depend on LibGDX.

Support
====================
Issues can be placed on the issue tracker. The best way of contacting me would be on IRC. Feature requests will be looked over and implemented if needed.

License
====================
The libgdx-udp-extension or gdx-udp is licensed under the Apache 2.0 License. This simply means you are free to use the library for commercial and non-commercial projects! If you modify the source, you are also not required to share the modifications or contribute them back upstream (but if you find a criticial bug, it would be nice to contribute a fix back!).
