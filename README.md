# intrasonics-portaudio

A [Node.js](http://nodejs.org/) [addon](http://nodejs.org/api/addons.html) that provides a wrapper around the [PortAudio](http://portaudio.com/) library, enabling an application to record and play audio with cross platform support. With this library, you can create [node.js streams](https://nodejs.org/dist/latest-v6.x/docs/api/stream.html) that can be piped to or from other streams, such as files and network connections. This library supports back-pressure.

This is a fork of [naudiodon](/Streampunk/naudiodon)

Note: This is a server side library. It is not intended as a means to play and record audio via a browser.

## Installation

Install [Node.js](http://nodejs.org/) for your platform. This software has been developed against the long term stable (LTS) release. For ease of installation with other node packages, this package includes a copy of the dependent PortAudio library and so has no prerequisites.

Naudiodon is designed to be `require`d to use from your own application to provide async processing. For example:

    npm install --save intrasonics-portaudio

For Raspberry Pi users, please note that this library is not intended for use with the internal sound card. Please use an external USB sound card or GPIO breakout board such as the [_Pi-DAC+ Full-HD Audio Card_](https://www.modmypi.com/raspberry-pi/breakout-boards/iqaudio/pi-dac-plus-full-hd-audio-card/?tag=pi-dac).

## License

This software is released under the Apache 2.0 license. Copyright 2017 Streampunk Media Ltd.

This software uses libraries from the PortAudio project. The [license terms for PortAudio](http://portaudio.com/license.html) are stated to be an [MIT license](http://opensource.org/licenses/mit-license.php). Streampunk Media are grateful to Ross Bencina and Phil Burk for their excellent library.
