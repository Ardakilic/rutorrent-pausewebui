ruTorrent Pause WebUI
----------

**Note:** This repository is simply a mirror for original Google code repository, which is hosted at [https://code.google.com/p/rutorrent-pausewebui/](https://code.google.com/p/rutorrent-pausewebui/). This repository simply aims to make a mirror on GitHub, since the Google Code will be closed soon and since no action was taken, I decided to manually export myself. 

All credits goes to the original author directly.

----------

Plugin to pause the refresh timer, and add a button to manually refresh the page.

Installation
----------

download, unzip and add to the rutorrent plugins directory.

Installing via git is also an option. Assuming your rutorrent root directory is `/var/www/rutorrent/` issue the following commands:

```shell
cd /var/www/rutorrent/plugins/
git clone https://github.com/Ardakilic/rutorrent-pausewebui.git pausewebui
```

Usage
----------

This plugin is very simple (but elegant).

It adds 2 buttons to your menubar. Upon clicking the "pause" button, rutorrent will stop refreshing automatically. You can manually refresh the ui by clicking the "refresh button" This is the button to the right of the pause button.

After clicking the "pause" button, it will change to a "play" button.

this plugin will also stop rutorrent from refreshing automatically when the tab isn't in use via the web browser, saving bandwidth, cpu cylces and memory.

[http://code.google.com/p/rutorrent/wiki/PluginPause](http://code.google.com/p/rutorrent/wiki/PluginPause)

[https://github.com/Novik/ruTorrent/wiki/PluginPause](https://github.com/Novik/ruTorrent/wiki/PluginPause)

Contribution
----------

If the original author doesn't export the project to GitHub, You can feel free to make Pull Requests to this repo, I'll gladly consider them.