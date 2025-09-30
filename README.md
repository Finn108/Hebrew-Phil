# Phil, a crossword maker (Hebrew RTL version)

<img src="images/screenshot.png">

Phil helps you make crosswords, using client-side JavaScript.
* Import & export .xw ([JSON](https://www.xwordinfo.com/JSON/)) or .puz files.
* Use the built-in dictionary, or any text file you want.
* Print to PDF.
* Create a New York Times submission in seconds.

New to this fork:
* [Bob Copeland's](https://github.com/bcopeland) JS auto filler
* Custom grid sizes
* NYT Sunday grid (21×21) PDF submissions
* Strict matching mode (matches filtered by crossers' constraints)
* Interactive stats
* Dark mode
* Mobile support
* Rebus
* Circles and shades
* Undo/redo
* Match letter histograms

TODO:
* copy current word into Onelook/xwordinfo pattern
* allow circles and shades in same puzzle or even square
* grid generation CSP: width, height, number of words, mean word length, block %, open %, sym, at least n words of length m
* larger wordlist, grid bank
* Scored word list
* Show word scores in matches list, sort alphabetically or by score
* Character classes in squares, with vowel and consonant shorthands
* Option move/delete
* Add to and remove from wordlist
* Save edited wordlist
* Autofill region, ui integration, scored word lists, choose among fills
* Better responsive layout

## Acknowledgements

Phil uses [Font Awesome](https://github.com/FortAwesome/Font-Awesome/) and [fonticon](https://github.com/devgg/FontIcon) for icons, [jsPDF](https://github.com/MrRio/jsPDF/) and [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable/) for generating PDFs, [Chart.js](https://github.com/chartjs) with the [datalabels](https://github.com/chartjs/chartjs-plugin-datalabels) plugin for charts, and [HyperList](https://github.com/tbranyen/hyperlist) for virtual scrolling of wordlist matches. Thanks to those who documented the .puz file format [here](https://code.google.com/archive/p/puz/wikis/FileFormat.wiki). The default wordlist is [Peter Broda's wordlist](https://peterbroda.me/crosswords/wordlist/).

## Getting started

To use this fork:

1. Go to https://jmviz.github.io/Phil/.

To run this fork locally:

1. Clone this repository.

2. Enter the Phil directory.

3. Run a local webserver. For example, with Python 3:

   ```
   python -m http.server 8000
   ```

4. Point your browser to [localhost:8000](http://localhost:8000).

## Crossword resources

* [OneLook](http://onelook.com/) and [Crossword Tracker](http://crosswordtracker.com/) search engines
* [XWord Info](https://www.xwordinfo.com) (some features require membership)
* [Crosshare](https://crosshare.org), a nice site to construct and share crossword puzzles, and play puzzles shared by others
* [Collected wordlists](http://wiki.puzzlers.org/dokuwiki/doku.php?id=solving:wordlists:about:start) of the National Puzzler's League
* [Crossword theme categories](http://www.cruciverb.com/index.php?action=ezportal;sa=page;p=70)

## License
Licensed under [the Apache License, v2.0](http://www.apache.org/licenses/LICENSE-2.0) (the 'License').

Unless required by law or agreed in writing, software distributed under the License
is distributed on an **'as is' basis, without warranties or conditions**, express or implied.
See the [License](LICENSE.txt) for the specific language governing permissions and limitations.

Original [Phil](https://github.com/keiranking/Phil) Copyright &copy; 2017 [Keiran King](http://www.keiranking.com/).
