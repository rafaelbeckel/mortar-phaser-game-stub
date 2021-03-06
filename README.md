# Phaser Game Stub

This is a small game template to build games using the [Phaser Framework](http://phaser.io).

This is part of the [mortar](https://github.com/mozilla/mortar/) template collection for building [Open Web Apps](https://developer.mozilla.org/en-US/Apps).


## Downloading

There are a few ways to get this template:

If you use [Git](http://www.git-scm.com/):

````bash
git clone https://github.com/firefoxos-gamedev/mortar-phaser-game-stub.git
````

Or download the latest version in this [ZIP file](https://github.com/firefoxos-gamedev/mortar-phaser-game-stub/archive/master.zip).


## Phaser Framework

[Phaser](http://phaser.io) is a proven open source framework for creating HTML5 games. It has many features such as input control, game loops, camera control, tilemaps and more all baked in. Its a great tool to help you create your game and not focus on trivia stuff that is not related to your project or vision.

### Updating phaser
The phaser framework in this template was installed using the [Bower](http://bower.io) tool. You can update to newer versions easily if you have bower installed. To update phaser use:

```bash
$ bower update
```

## Code walkthrough
The code is contained in three files &mdash boot.js, preloader.js, game.js &mdash each serves a different purpose and is explained below:

### main.js
This file register our listener for the *DOMContentLoaded* event. This event will fire once all the html/css/js files are loaded.

In this file we setup the Phaser framework and register our game states. A game can have multiple game states. This stub has two states each defined in their own file.

### preload.js
This is the first game state. Its responsible for loading all the assets needed for this stub (in this case the graphic files). Once all the files are loaded, it moves to the next state.

### game.js
This another game state. It is our **gameloop** in a real game, it would be where you process user input and update your display.

Basically the **preload** state loads the resources to be used in the **game** state.
