Send any video to your AirPlay device.
=============================

send2airplay is a command line script for streaming videos from your drive to Apple's 
[AirPlay](http://en.wikipedia.org/wiki/AirPlay) remote playback protocol.

## Installation 

With [npm](http://npmjs.org):

    npm install send2airplay -g

From source:

    cd ~
    git clone https://github.com/guerrerocarlos/send2airplay.git
    npm link send2airplay/

## Usage:

    send2airplay <file> <optional:port>

## Example

    $ send2airplay ~/Download/52.mp4
    Sending /Users/youruser/Download/52.mp4 by Airplay...
    Serving directory: /Users/youruser/Download/ on port 4007
    Calling Play in: http://192.168.0.101:4007/52.mp4
    Playing file 52.mp4 in your AirPlay Device

## Extra

For convenience a 's2a' command alias is also created.

    $ s2a ~/Download/52.mp4
