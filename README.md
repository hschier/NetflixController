Control Netflix in your browser with a gamepad or controller using this Chrome extension.

## TODO
* Dynamically determine whether a page has a billboard or not
* Firefox/Edge support (convert manifests, fullscreen action)
* Continue mapping navigation controls to additional page elements
* Support non-standard gamepad mappings / offer way to configure mappings
* Configure right joystick to control a virtual mouse
* Timeout page readiness checks (useful in case of no internet connection)
* Improve plugin design to be extendable for other websites
* Come up with a better plugin name, maybe considering future extendability (Flixability, Joyflix, Netstix)
* Dual action hints for action pairs like volume up/down
* CSS classes for content outlines
* Fix visual bug that occurs on some billboard MyList buttons
* Increase size of virtual keyboard and scale inserted UI elements according to page size
* Hide jump 10s actions when unavaiable (player class 'preplay'?)
* Identify interactive videos and only apply related settings if needed
* Support for /title pages and expanded video elements
* Fix bug where search page handler does not finish loading until keyboard is closed when only one character has been entered into the search bar
* Scroll up to search box when keyboard is opened while viewing a lower portion of the page
* Organize page handler logic such that navigatables have clean access to the enclosing page handler
* Use mutation observer instead of static delay to determine when jawbone is ready for focus
* Rewrite Billboard query logic using similar logic as in Jawbone and maybe create a superclass

## Libraries and Materials Used
* [pseudo:styler](https://github.com/TSedlar/pseudo-styler) - Allows for forcing an element to be styled with a pseudo-class.
* [Gamepads.js](https://github.com/FThompson/Gamepads.js) - A simple JavaScript module for tracking Gamepads and events pertaining to their usage.
* [Chrome Live Storage](https://github.com/FThompson/ChromeLiveStorage) - A module that provides `chrome.storage` data as native JavaScript objects that automatically synchronize between all extension views (background, content scripts, popups, options, etc.).
* Project icons courtesy of https://material.io/icons/ and https://iconfu.com.
* Many thanks to [Tyler Sedlar](https://github.com/TSedlar) for creating pseudo:styler and for letting me bounce ideas off of him throughout development of this project.