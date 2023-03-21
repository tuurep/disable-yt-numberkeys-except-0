# Disable YouTube Seek by Number (Except 0)

This is a fork of https://github.com/timmontague/youtube-disable-number-seek

## Why?

The addon prevents losing your place on a video if you accidentally press a number key. But there were some of us who still wanted to use <kbd>0</kbd>, because it goes to the start of the video and is useful for quickly resetting a video from the beginning.

Fork born from the discussion in this issue: https://github.com/timmontague/youtube-disable-number-seek/issues/3

## Other fixes

Remove permissions for domains `*.invidio.us/*`, it now operates under [instances](https://api.invidious.io/)

Todo: Enable permissions for any YouTube frontend which has these keybinds

* done for example in [SponsorBlock](https://github.com/ajayyy/SponsorBlock)

Todo: Add option to enable/disable 0 and rename both this repo and addon

## Further thoughts

Why not just add a toggle for all of the YouTube key shortcuts (`j`, `k`, `l`, `f`, `t`, `m`...)?

* yes, that's where this is logically heading.. but I would like to start a whole new addon for that.
