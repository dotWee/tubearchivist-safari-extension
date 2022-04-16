# TubeArchivist Companion Extension for Safari

The extensions works just like the Chrome/Firefox version, it shares the same code using a git submodule reference to [browser-extension](https://github.com/tubearchivist/browser-extension).  

Most of this repo’s code is pure boiler plate code. Support for **Safari on macOS Monterey** is tested and **works without issues**.  
Targets for **Safari on iOS & iPadOS exist** but are currently **untested** (but probably work, since no changes on macOS Target where neccessary).  

## Setup

Clone the repository:

`$ git clone https://github.com/dotWee/tubearchivist-safari-extension`

Change into the local clone and sync its submodule [browser-extension](https://github.com/tubearchivist/browser-extension):

`$ git submodule update --init --recursive`

Then simply open the `Companion.xcodeproj` with Xcode.

Simply build and run, then a window should appear directing you to Safari's extension preferences, where you can activate the extension.
