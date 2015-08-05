# Open in Browser Workflow for Alfred
This [Alfred](http://www.alfredapp.com) workflow opens the current active tab of a browser in a different browser.

It's based on Andrew Curtis-Black's workflow [Open current Safari tab in Chrome](http://www.alfredforum.com/topic/1875-open-current-safari-tab-in-chrome-improved/) which itself is based on another workflow [of the same name](http://www.alfredforum.com/topic/533-open-current-safari-tab-in-chrome/).

I extended the existing workflows to better suit my needs:  
I browse the web in Safari, but mainly work in Chromium, so I switch between the two browsers heavily. In addition, I don't have Flash installed on my Mac, so whenever I come across some content that uses Flash I fire up Google Chrome to view it (or I ignore it completely).

## Installation
To install the workflow, download `openInBrowser.alfredworkflow` and double-click.

## How to Use It
Trigger the workflow with `openinchrome`, `openinsafari` or `openinchromium`, depending on which browser you want to open. The script detects the current active browser and retrieves the active tab's URL from it. 

The workflow will not do anything when neither Safari, Chromium or Chrome are the frontmost/active window to avoid confusion on which tab to clone.

### Currently Supported Browsers
- Safari
- [Chromium](https://www.chromium.org/Home)
- [Google Chrome](https://www.google.com/chrome)

### Turning on/off Notifications
You can turn off all notifications by removing or disconnecting the **Post Notification** object in the Alfred workflow window. If you only want to receive specific notifications, enable/disable them by commenting them out in the AppleScript.

## Download
[Open in Browser Workflow for Alfred](https://github.com/alexanderhuth/alfred-open-in-browser-workflow/releases/download/v1.0/openInBrowser.alfredworkflow)

## Version History
### 1.0 - July 30, 2015
- Initial release
- Supports Safari, Google Chrome & Chromium
- Re-uses code from [Open current Safari tab in Chrome](http://www.alfredforum.com/topic/1875-open-current-safari-tab-in-chrome-improved/) workflow

## Credits
[Icon](http://www.flaticon.com/free-icon/global-refreshment_13618) made made by [Freepik](http://www.flaticon.com/authors/freepik) from [www.flaticon.com](http://www.flaticon.com), licensed by [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/).  
Many thanks to both Subject22 (Andrew Curtis-Black) and Runar from [alfredforum.com](http://www.alfredforum.com), whose workflows made my life so much easier and now act as a base for this workflow.
