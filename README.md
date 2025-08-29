# Extension's original author + a few words by rado84

I do not know who the original author is. The extension has been abandoned in 2021 and was working almost fine ever since, I simply added a few lines of code to enable closing of the sidebar by clicking on the toolbar icon and also to make sure it works with modern versions of Firefox, Waterfox and anything-fox. If you know who the author of the original extension is or if you're him/her, let me know and I'll include their/your name everywhere.
I decided to make a fork of the original extension because I really like it and I don't want it to die some day.

# Downloads sidebar web extension

This extension will display a list of your latest downloads in the Firefox sidebar.

Since this is a reborn version of the extension, the latest version is **0.0.1**

## How do I use this?

Open your Firefox sidebar and choose "Downloads" from the top drop-down list.

Keyboard shortcut is **F2**. In the browser this key does absolutely nothing, that's why I chose it over the original key which was F4. But if you decide to close the browser with Alt+F4, that would still open the sidebar. Hence, the changed default key to open the sidebar.

There is also a browser toolbar button which opens the Downloads sidebar.

### Features

* pause, resume, cancel, retry, erase download
* copy download link
* open download page link
* show downloaded file in folder
* open downloaded file directly by clicking on its icon, or double-clicking anywhere else
* erase all recent downloads that are not active (active = downloading or paused)

### Dark theme is still impossible
I spent 4 hours in attempts to make a dark theme work but... not a chance, it just keeps breaking. The only way to have your own theme (dark or otherwise) is to directly edit /sidebar/panel.css which I did for my browser. The file named "0.0.2 - my dark theme.7z" contains a screenshot of my dark theme for the extension, an xpi with that dark theme and a zip file which you can unpack anywhere and if you're aware with CSS, edit the file in question to make your own theme. But after that you'll have to use the option "Install add-on from file". I haven't uploaded this version on AMO because not everyone will like my theme and I don't wanna push something you may or may not like.

### Dark theme making
If you're an ethusiast who really wants to try and make a "Preferences" page with editable colors (which actually work), feel free to do so. I'll test it and if it really works, I'll merge your files/code with the current and you'll be fully credited about it. Then that version will go on AMO as an update.

### Credits

* uses Ractive.js (https://github.com/ractivejs/ractive)
* downloads icon by Pixel perfect on flaticon (https://www.flaticon.com/authors/pixel-perfect)
* play and pause icons by ionicons (http://ionicons.com)
* cancel, copy, open external, folder and retry icon from firefox (https://design.firefox.com/icons/viewer/)

### Contributions (thank you!)

* **Josep Maria Salvia Hornos** (https://github.com/josalhor)
  * approximate download speed
  * approximate time remaining for a download
  * updated icons
  * UI adjustments so the extension better fits with the Firefox design guidelines
  * variable speed and time indicators
  * various fixes

### Requested features

* dark theme
For the moment I (rado84) don't know how to make the sidebar work with the integrated dark theme of the browser. If someone knows how to do that, I'll be more than happy to add your code as a contribution to the reborn extension and ofcourse I'll give you all the credit for this contribution.

### Features that are not possible to implement

As of 2018/08/15 it's not possible to implement the following features, because the API is intentionally limiting them or offers no replacement:

* auto-opening panel after downloading is done
* auto-opening file after downloading is done
* dragging and dropping using the official sidebar API doesn't seem possible
* keyboard shortcut modification

