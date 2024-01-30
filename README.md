# iofthetiger - High Performance Cross Platform Async IO Library for Zig

This library is pretty much the [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle)
IO library with the TigerBeetle specifics removed, to make it a more general purpose async
IO library for Zig programs. It works on Linux, macOS, and Windows.

The tests in [tests](src/test.zig) show some sample usage, and there's a full sample
[multithreaded web server](src/sample_web_server.zig) too. You can build and run the sample
web server with `zig build run server`.
