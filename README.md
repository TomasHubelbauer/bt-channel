# [Bluetooth Channel](https://tomashubelbauer.github.io/bt-channel/)

This repository is an experiment in using Web Bluetooth to exchange SDP and ICE in order to establish a
WebRTC peer connection with a data channel.

It is related to my other experiment, [QR Channel](https://github.com/TomasHubelbauer/qr-channel).

**[I have found this is currently not possible using Web Bluetooth](https://github.com/WebBluetoothCG/web-bluetooth/issues/231)**

## Running

This repository is a static file web application, you don't need to compile or build anything.

Just `start index.html` or see the [**online demo**](https://tomashubelbauer.github.io/bt-channel/).

## To-Do

### Wait for beacons support in Web Bluetooth

https://github.com/WebBluetoothCG/web-bluetooth/issues/231

### Prototype an iOS application exposing its bundle/group in Files using Web Bluetooth

The iOS application should be able to advertise unlike the web API and Chrome should be
able to use Web Bluetooth to connect to it. And potentially hand over to another/default
browser once the connection is established using a URL with WebRTC SDP in arguments.
