\# Snehitara Chai Adda



\*\*A Kannada tea-shop experience inspired by Bengaluru's neighborhood chai culture and the idea that a tea stall is the original social network.\*\*



ಸ್ನೇಹಿತರ ಕೂಟ ಚಹಾ ಅಡ್ಡಾ



\## About



Snehitara Chai Adda is a responsive, single-page virtual tea shop. It combines a Kannada-English interface with interactive chai-making visuals, a traditional tea menu, a simple billing counter, ambient effects, and stories celebrating the culture of Bengaluru tea stalls.



\## Features



\- \*\*Tea and coffee menu:\*\* Select from seven drinks, view prices, and add an item to the bill.

\- \*\*Animated chai glass:\*\* Change the selected drink and replay the pouring animation.

\- \*\*Billing counter:\*\* Adjust quantities, review the total, clear the bill, and try a simulated cash payment.

\- \*\*Ambient controls:\*\* Toggle the lamp and monsoon rain, or choose from visual presets.

\- \*\*Memory archive:\*\* Browse friendship-themed memories, copy a memory, and explore heritage cards and newspaper content.

\- \*\*Kannada music player:\*\* Play or pause "Jotheyali Jothe Jotheyali" with a YouTube link available if the local audio cannot be played.

\- \*\*Keyboard shortcuts:\*\* Press `Space` to pour chai and `C` for the counter sound.

\- \*\*Responsive design:\*\* A warm, dark theme with Kannada and Latin typography, designed for mobile and desktop screens.



\## Built With



\- HTML5

\- CSS3

\- Vanilla JavaScript

\- Tailwind CSS via CDN

\- Google Fonts: Noto Sans Kannada, Noto Serif Kannada, Playfair Display, and Plus Jakarta Sans



\## Run Locally



Keep the HTML page and audio asset together in the same directory:



```text

teashop.html

jotheyali-jothe-jotheyali.m4a

```



From that directory, start a local static web server:



```bash

python -m http.server 8000

```



Then open \[http://localhost:8000/teashop.html](http://localhost:8000/teashop.html).



The page uses CDN-hosted Tailwind CSS and Google Fonts, so an internet connection is needed for those assets. Serving the page over HTTP is recommended for reliable media playback; some browsers restrict audio or YouTube links when a page is opened directly as a `file://` URL. M4A/AAC playback depends on browser codec support.



\## Publish with GitHub Pages



1\. Upload `teashop.html`, `jotheyali-jothe-jotheyali.m4a`, and this README to your repository.

2\. Enable GitHub Pages in the repository settings.

3\. Open the published page at `https://<username>.github.io/<repository>/teashop.html`.



To make the page load at the repository's root URL, rename `teashop.html` to `index.html` before publishing. Keep the audio file beside the HTML page so its relative URL continues to work.



\## Project Notes



\- This is a static front-end project. The billing counter is a demonstration and does not process real payments or store orders.

\- The audio file is a user-provided M4A/AAC asset. Confirm you have the rights needed to publish it with the repository.

\- No open-source license is included. Add a `LICENSE` file if you want to grant others permission to reuse or modify the project.



