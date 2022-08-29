# Left

<a href="http://wiki.xxiivv.com/Left" target="_blank"></a>Left is <b>distractionless plaintext editor</b> designed to quickly navigate between segments of an essay, or multiple documents. It features an auto-complete, synonyms suggestions, writing statistics, markup-based navigation and a speed-reader.
 
Learn more by reading the <a href="https://100r.co/site/left.html" target="_blank" rel="noreferrer" class="external ">manual</a>, or have a look at a <a href="https://www.youtube.com/watch?v=QloUoqqhXGE" target="_blank" rel="noreferrer" class="external ">tutorial video</a>. If you need <b>help</b>, visit the <a href="https://hundredrabbits.itch.io/left/community" target="_blank" rel="noreferrer" class="external ">Community</a>.

## Install & Run

You can download [builds](https://hundredrabbits.itch.io/left) for **OSX, Windows and Linux**, or if you wish to build it yourself, follow these steps:

to run: 
```
git clone https://github.com/hundredrabbits/Left.git
cd Left/desktop/
npm install
npm start 
```

to produce the desktop apps run: (you might have to change some paths in package.json for this to work) 
```
npm run build 
```

## Extras

- This application supports the [Ecosystem Theme](https://github.com/hundredrabbits/Themes).
- Support the original project through [Patreon](https://patreon.com/100).
- Left's source code is licensed under [MIT](https://github.com/hundredrabbits/Left/blob/master/LICENSE) and the **images, text and assets** are licensed under [BY-NC-SA 4.0](https://github.com/hundredrabbits/Left/blob/master/LICENSE.by-nc-sa-4.0.md). View individual licenses for details.
- Pull Requests are welcome!


## This is a forked repo of Left where I have been making change to make it work with my flow, so far those change include the following on bmaster branch.
- options tab with the following features: 
   - Save Window Size - saves current window size to local storage and resizes/centers window after app starts up.
   - Set Text Area Width - allows you to change the text area size by supplying a number and hitting enter, esc, or right clicking in the app
   - Set Navi Header Chars to Show - allows you to limit the number of characters the headers/comments display in the navigation bar
- navi bar spacing to make page/header more distinguishable 
- save defaults to txt file type with option to use all file types
