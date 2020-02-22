# TCI library
TCI – Transceiver Control Interface is the network interface for control, data transfer and synchronization between a transceiver/receiver, logger, digital software, skimmer, other software and external power amplifier, band filters, antenna switch, radio station controller and other devices.
The library implements the client part for connecting to the server.

## Motivation
The TCI Protocol is implemented on top of websocket , but websocket is not available on some platforms or it is very difficult to build libwebsocket and not all developers want to spend time on it.
tcl_library is implemented in such a way that compilation for different platforms was as easy as possible and did not use dependencies on third-party libraries.

### Planned features
* Internal implementation of websockets client
* Compile-time text processor for string commands

## Dependencies
* c++17
