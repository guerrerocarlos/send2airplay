Send any video to your AirPlay device.
=============================

send-to-airplay is a command line script for streaming videos from your drive to Apple's 
[AirPlay](http://en.wikipedia.org/wiki/AirPlay) remote playback protocol.

## Installation 

With [npm](http://npmjs.org):

    npm install send-to-airplay -g

From source:

    cd ~
    git clone https://github.com/guerrerocarlos/send-to-airplay.git
    npm link send-to-airplay/

## Usage:

    send-to-airplay <file> <optional:port>

## Example

    $ send-to-airplay ~/Download/52.mp4
    Sending /Users/youruser/Download/52.mp4 by Airplay...
    Serving directory: /Users/youruser/Download/ on port 4007
    Calling Play in: http://192.168.0.101:4007/52.mp4
    Playing file 52.mp4 in your AirPlay Device

## Extra

For convenience a 's2a' command alias is also created.

    $ s2a ~/Download/52.mp4
