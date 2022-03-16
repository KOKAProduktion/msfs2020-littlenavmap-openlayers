![Screenshot (65)](https://user-images.githubusercontent.com/3401839/111709694-62b53e00-8848-11eb-9be1-d8b922f9c081.png)

# msfs2020-littlenavmap-openlayers

_Pan and scroll-able Little Navmap in VR_

This is a Microsoft FlightSimulator 2020 in-game panel window embedding [Little Navmap](https://albar965.github.io/) via the [littlenavmap-openlayers](https://github.com/KOKAProduktion/littlenavmap-openlayers) application. It is required to make the [littlenavmap-openlayers](https://github.com/KOKAProduktion/littlenavmap-openlayers) features available in-game.

Built upon [bymaximus/msfs2020-toolbar-window-template](https://github.com/bymaximus/msfs2020-toolbar-window-template)

**State:** Prototype ([Known Issues](https://github.com/KOKAProduktion/littlenavmap-openlayers#possible-issues--concerns))

## Installation

- Install the required [littlenavmap-openlayers](https://github.com/KOKAProduktion/littlenavmap-openlayers) web UI for LNM.

- To install this panel, just copy the `msfs2020-littlenavmap-openlayers` folder to your MSFS2020 `Community` folder.

- Make sure the **LITTLENAVMAP** panel is turned on inside the toolbar settings:

![Screenshot (177)](https://user-images.githubusercontent.com/3401839/154785163-817d39f0-2c9d-4110-aa08-5a02e18f8a62.png)

- If your LNM server runs on a host/port other than its default settings adjust `msfs2020-littlenavmap-openlayers\html_ui\InGamePanels\WebPage\CustomPanel.js` (L:103) accordingly.

Note: LNM and its web server must be runnning in order to use this panel
## Credits

Thanks to [@bymaximus](https://github.com/bymaximus) for sharing his MSFS2020 in-game panel projects
