## Minimal Startpage

This is my minimal startpage. It's as minimal as you can get - there is nothing on screen. This startpage in entirely controlled by your keyboard.

## Features

* Keyboard Controlled
* Controllable Binds
* Usable Offline
* Loads Instantly

## How are the binds set?

Simple. The binds are all controlled by the `main.js` file, located [here](https://github.com/HaydenSD/startpage-minimal/blob/master/js/main.js). This is written in JQuery (which is loaded and sourced within the project allowing for offline usage) and it's pretty simple to edit. Once the `document` loads, it checks for key presses. Then, if the key presses match the binds that are set, it loads a new webpage. The key bindings are key codes, and a list can be seen [here](https://css-tricks.com/snippets/javascript/javascript-keycodes/).

## Todo

* DuckDuckGo Search Bind
* Shell Bind
