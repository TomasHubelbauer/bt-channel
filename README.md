# [BlueTooth Channel](https://tomashubelbauer.github.io/bt-channel/)

This repository is an experiment in using Web Bluetooth to exchange SDP and ICE in order to establish a
WebRTC peer connection with a data channel.

It is related to my other experiment, [QR Channel](https://github.com/TomasHubelbauer/qr-channel).

## Running

This repository is a static file web application, you don't need to compile or build anything.

Just `start index.html` or see the [**online demo**](https://tomashubelbauer.github.io/bt-channel/).

## Contributing

It looks like Web Bluetooth can only pair with other devices and use their services, it doesn't seem to be able to
contribute a new service to the BT device of own machine. This is necessary (I think) to establish a bi-directional
communication between two machines. If it really lacks, it is a deal breaker for this use case.

- [ ] Figure out https://stackoverflow.com/q/53925419/2715716
