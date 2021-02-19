## installation

`yarn` or `npm install` 

## run 

`yarn start` or `npm start`

## issues

This frame shows a few different ways that media emulation is reset. (black background: emulation is active, white background: it's not.)

_This assumes a system in light mode_

* Opening devtools will remove all emulation
* Clicking the append button adds an iframe to the page, this causes flashes (click a few times) that show emulation very quickly switching back and forth
*Navigating to a new URL will remove emulation right before loading the new url, also causing a flash
