WebSpeechAPI
============

A simplified Web Speech API and input matching system demo

This has been tested on reasonably recent versions of Chrome for OSX and Android. On Android, it makes a little ding noise every so often, but this doesn't seem to affect anything. It should work on Safari, too.

**Important**: The Web Speech API is really not suited for non-SSL servers. It will prompt the user for microphone access after 60 seconds of silence or any other time it stops/errors out. I'd recommend getting a cheapo (<$10) cert to make any public sites featuring voice interactivity or a self-signed cert to just play around with it. It took me longer than I'd like to admit to sort out Node.js and HTTPS, so I might end up writing an SSL for Cats guide at some point in the future.

To view a fully fleshed out version of this demo, see my [personal website](https://benwasser.com). I put the matching system on the server instead of the front-end, but the logic is the same as this demo.