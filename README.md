# dome

michcio's writing a podcast player [again](https://github.com/michcioperz/dom). sort of

## design

i'm going to regret this

there is a player client you run on your computer which receives urls to play, plays them with mpv, and then reports back that playback completed

it receives the url from the central controller API which also has a web UI for choosing things to play

the web UI gets the lists of things that can be played from source APIs which are separate services (this has a nice property where some services can be proprietary if you're not courageous enough to out an indie radio company with hidden in plain sight patron-only json feeds)