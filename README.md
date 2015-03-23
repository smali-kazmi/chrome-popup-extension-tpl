# Google Chrome Popup Extension
> A simple Google Chrome Popup Extension Template for starters 

![Screenshot](http://i.imgur.com/y7f9Vkd.png)

## Jump to Section

* [Getting Started](#getting-started)
* [Installation](#installation)
* [Usage](#usage)

## Getting Started

This package has been made to quickly get yourself up and running with making a new Google Chrome extension.  The basic structure of this package is as follows:

    - css/
		-- bootstrap.min (Edited, please see "important notes")
		-- custom.css (Contains small style tweaks, edit this file at your will)
    - images/
        -- icon-16.png
        -- icon-32.png
        -- icon-48.png
        -- icon-128.png
			--- Please note, this is just a filler image for your extension.
	- js/
		-- popup.js
    - manifest.json
	- popup.html
	- README.md
	
### Installation

- Please either clone this repository or download as a ZIP file.
- Extract the contents into your preferred working directory.
- Open your Google Chrome browser.
- Enter `chrome://extensions/` into the address bar.
- Ensure "Developer Mode" is ticked/enabled in the top right.
- Click on "Load unpacked extension...".
- Navigate to your extracted directory, and click "OK".
- Your basic extension template should now be alongside your address bar, showing the Google Chrome logo.

## Usage

This package is standalone.  Please visit the Google Developer documentation if you wish to know more about Extension creating:

http://developer.chrome.com/extensions/getstarted.html

### Files to edit

The main files you will need to edit are:

> manifest.json

- This contains all of your extension information.
- The default popup window for this extension is called `popup.html`.

> popup.html

- Contains the basic HTML boilerplate, edit at your will.

> css/style.css

- Contains extension height and width.
