# Beatbox

Live beatbox sample replacement in the browser. Created at the [Protothon No. 4 Rethinking Real-Time](http://protothon.com/events/chrome-media/) hack day.

## Quick start guide

1. Install the latest [Chrome Canary browser](https://tools.google.com/dlpage/chromesxs)

2. Enter `chrome://flags` in the address bar and hit return. Search the page for 'web audio input' and check it's enabled.

3. Visit the [live demo](http://screamingrobots.com/beatbox/) and allow audio access (and camera, if you want to test the filter effect by waving a slice of pizza around).

4. Beatbox! You don't have to sound good, just make subby bass and sizzling snare sounds. 

5. Change drum sample sounds with the top drop down menu.

### Note

The effects controls at the top don't work, that's the rough GUI that wasn't finished. The top genre drop-down will change beat sounds, though.

## Development

Install dependencies

* `npm install grunt -g`
* `npm install bower -g`
* `npm install`
* `bower install`

Start grunt watcher

* `grunt watch`
