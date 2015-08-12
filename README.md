# Polymer-MDL

[Material Design Lite](http://getmdl.io) as Polymer elements.

## Status

- Proof of concept WIP
	- CSS class are passed and set correctly to the elements
	- JS-injected elements don't work

- some layout and navigation elements ported

## Installation (for dev)

Following [this guide](https://www.polymer-project.org/1.0/docs/start/reusableelements.html),
1. `git clone` this repo somewhere.
2. make sure you have npm, bower and polyserve installed (`npm install -g bower polyserve` if not)
3. `bower install` (or `bower install bower.json` if the former doesn't work) to install the dependencies.
4. `polyserve` and open `localhost:8080/components/polymer-mdl/example.html` to see it running

## Usage

Instead of creating divs with the specific MDL classes, create elements
named after those specific classes.

Instead of this:

	<div class="mdl-layout">
	</div>

Write this:

	<mdl-layout>
	</mdl-layout>

### Example


## Catalog
