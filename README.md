# Greek Vocab Cards

A mobile-friendly flashcard app for New Testament Greek vocabulary, built chapter by chapter alongside *Basics of Biblical Greek*.

- **Flashcards**: tap to flip, mark "Got it" or "Review again", reshuffle or restart in textbook order
- **Test what I don't know yet**: one deck of every card not yet marked known
- **Search**: Greek (accents optional) or English, across every chapter
- **Overall progress**: words memorized and percent of New Testament word occurrences covered
- **Grammar Charts** tab: stop consonants, πᾶς, first/second declension, εἰμί

## Install it as an app

Open the GitHub Pages site on your phone, then:

- **iPhone / iPad (Safari)**: Share button → **Add to Home Screen**
- **Android (Chrome)**: ⋮ menu → **Install app** (or **Add to Home screen**)
- **Desktop (Chrome / Edge)**: click the install icon in the address bar

Once it has loaded one time, it also opens offline. When you're online it always loads the newest version.

## Files

- `index.html`: the whole app, one self-contained file with no build step
- `manifest.webmanifest`, `icons/`: what makes it installable
- `sw.js`: offline support

Progress is saved in the browser's local storage on each device, so it isn't shared between your phone and your computer.

## Host it

Settings → Pages → deploy from `main`, root folder.
