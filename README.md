To get a working Dirac

1. clone this repo
2. install [chrome canary](https://www.google.com/chrome/browser/canary.html)
3. customize the script `./canary` so that it calls your canary (currently it's Mac-specific)
4. run the script, find the canary window, install [dirac extension](https://chrome.google.com/webstore/detail/dirac-devtools/kbkdngfljkchidcjpnfcgcokkbhlkogi)
5. run `boot dev` in this directory, wait until you hear a *-pling-*
6. open http://localhost:3000 in the canary window
7. you should see two lines of text "dirac-test" & "A label"
8. click the dirac icon right of the address bar
9. a window should open, looking like chrome devtools
10. go to the console, press CTRL+.
11. try evaluating some ClojureScript inside the console
