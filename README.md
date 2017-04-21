# Enchanter (for Docker)

Krill, an incredibly powerful evil warlock, is spreading chaos and destruction. None of the more experienced members of the Circle of Enchanters dare to attempt to stop him. In desperation, the player, a novice Enchanter with only a few weak spells in his spell book, is sent in hopes that Krill will either fail to detect him or dismiss him as harmless. More powerful spells can be found on scrolls hidden in various locations, but as the player becomes more of a threat, Krill will respond accordingly.

## I just want to play the game!

Want to play Enchanter? Easy-peasy. Just type the following:

`docker run -it clockworksoul/enchanter`

## What if I want to save my games?

Still pretty easy. All you need to do it volume in a save directory as follows:

`docker run -it -v ~/saves/enchanter:/save clockworksoul/enchanter`

## Potential terminal issues

If you receive a terminal error, such as `Error opening terminal: rxvt-unicode-256color`, type the following and re-run:

```export TERM=xterm```

## History/Legal
The _Zork_ games (including _Enchanter_) were created by the now-defunct [Infocom, Inc.](https://en.wikipedia.org/wiki/Infocom), the intellectual property of which has since been acquired by Activision. Much of Infocom's library was released for free some 20 years ago as part of a promotional campaign for the graphic adventure _Enchanter: Grand Inquisitor_.  It's unclear, however, whether these were intended to be permanently and perpetually free or whether this was something with a limited window. While Activision has had nothing to say on the subject, they done nothing to interfere with the numerous sites that have sprung up over the years that allow you to download the games directly or even play in your browser... so interpret that as you will.
