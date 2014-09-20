libwebsocket
============

Experimental C++ WebSocket Server Library


The library was originally developed and tested on *Raspberry Pi*. Now it is developed on desktop machine and it is back-ported periodically. So far it works nicely under **Raspberry Pi** with about **0% CPU load** and **0.3% memory consumption**. These stats may vary on other hardware or if the system has additional, third-party software installed.

It is still experimental and in process of implementation against [**RFC 6455**](http://tools.ietf.org/html/rfc6455).



Current Status
--------------

The library now can make successful handshake with the clients and it can respond to messages. As it is still in experimental phase it is not directly usable. See the road map below.

Example Code
------------

The experimental server is now also added here in github, but in additional repo: [libwebsocket-server](https://github.com/Rolice/libwebsocket-server).

Simple Roadmap
--------------

The current road map is divided below in few points:

* Callback Mechanism
* Threading and Polling
* SSL Support
* Compression Support
* C Compatible Linkage

The library is currently under development for linux platforms. There might be a Windows implementation as well with the advance and completion of the current road map points above.

Reference
---------------------------------------

Here are some repositories I have inspected and borrowed some ideas, code or pure logical flow from:

* https://github.com/katzarsky/WebSocket
* https://github.com/WebKit/webkit
