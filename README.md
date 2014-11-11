WebSpeechAPI
============

A simplified Web Speech API and input matching system demo

This might not work anymore as the Web Speech API has somehow gotten less reliable over time. Once it standardizes I'll probably take another stab at this, although this code should get you started (and the input matching system still works fine).

**Important**: The Web Speech API is really not suited for non-SSL servers. It will prompt the user for microphone access after 60 seconds of silence or any other time it stops/errors out. I'd recommend getting a cheapo (<$10) cert to make any public sites featuring voice interactivity or a self-signed cert to just play around with it. It took me longer than I'd like to admit to sort out Node.js and HTTPS, so I might end up writing an SSL for Cats guide at some point in the future.
