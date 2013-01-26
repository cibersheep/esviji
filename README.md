# esviji

A variation around the famous Bubble Bobble game, in which you have to destroy balls and gain points as long as you can!

To know how to play, please run the tutorial available on the launch screen of the game.

## Features

- Vectorial interface, scalled to fit any viewport size without any visual loss, optimized for portrait orientation
- Multiple interaction options: keyboard, mouse & touch
- Current game persistence: close your browser and resume your game when you return
- Full off-line support

This game came out of my mind 20 years ago thanks to the great platform that were [HP 48 calculators](http://en.wikipedia.org/wiki/HP-48_series) (I've had 3 of them). I loved playing Bubble Bobble, Tetris and other casual game on my HP, but was also eager to develop my own game (a sily habit I have to develop games to discover new platforms/languages), and came with this idea of a kind of mashup of Tetris and Bubble Bobble.

I never found a satisfying name for this game, so I now took "esviji", a word game on "SVG".

esviji is open source, under MIT licence, feel free to <a href="https://github.com/nhoizey/esviji">fork it on Github</a>, make pull requests and open issues for bugs and improvement ideas.

## Supported platforms

### Known to work on

- Most recent desktop browsers: Firefox, Chrome, Safari, Maxthon (this one's for Matthias)
- Some mobile browsers: iOS Safari, Firefox Mobile
- [Tell us!](http://twitter.com/esviji)

### Known to NOT work on

- Some desktop browsers: Opera (a bug on score handling)
- Some mobile browsers: Chrome Android
- [Open issues](https://github.com/nhoizey/esviji/issues?labels=Broken+browser+support&page=1&state=open)
- [Open a new issue!](https://github.com/nhoizey/esviji/issues/new)

## To do

Look at [the roadmap](https://github.com/nhoizey/esviji/issues/milestones?direction=asc&page=1&sort=due_date).

## Building blocks

- JavaScript, with a little bit of jQuery
- [Matthias](http://twitter.com/madsgraphics)'s awesome [SVGEventListener polyfil](https://github.com/madsgraphics/SVGEventListener) for SVG animate events in webkit (once again)
- [Craig Campbell](http://craig.is/)'s [mousetrap](http://craig.is/killing/mice) for keyboard controls
- [mohayonao](http://twitter.com/mohayonao)'s [Timbre.js](https://github.com/mohayonao/timbre) for sounds

## Thanks a lot to…

- [Jérémie](http://twitter.com/JeremiePat) for [inspiration about SVG](http://jeremie.patonnier.net/tag/SVG)'s [power](http://jeremie.patonnier.net/experiences/parisweb2011/animation.svg) and assistance finding great docs in [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/SVG)
- [Karl](http://twitter.com/karlpro) for his kind assistance on Opera issues (some were real bugs, some were my own mistakes)
- [Anthony](http://twitter.com/rik24d) for his kind assistance on Firefox issues (again, some were real bugs, some where MDN errors, some were my own mistakes)
- [Matthias](http://twitter.com/madsgraphics) for his SVG animate events polyfil

## Contributing

Please feel free to fork, fix and send me pull requests. Alternatively, [open issues](https://github.com/nhoizey/esviji/issues/new) for bugs and feature requests.

## License

esviji is released under the MIT License.

Copyright (c) 1992 Nicolas Hoizey <nicolas@hoizey.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

