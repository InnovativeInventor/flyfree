# Fly Free
Fly Free is a forever free fork of the now paid [Raven Reader](https://ravenreader.app) project.

## Install
Download from releases or build using :
```
yarn build
```

![newscreenshot](/newscreenshot.png)
![darkscreenshot](/darkscreenshot.png)
![sunsetscreenshot](/sunsetscreenshot.png)

## Features

- [x] Full Article Read
- [x] Subscribing to news feed
- [x] Marking as read/unread
- [x] Marking as favourite
- [x] Dark mode
- [x] Configurable cron job for refresh interval of feeds
- [x] Minimize app to tray and run in background
- [x] Open article link in external browser
- [x] Responsive
- [x] Exporting feed in OPML format
- [x] Importing feeds
- [x] Windows support
- [x] Linux support
- [x] Offline reading
- [x] Keyboard Shortcuts
- [x] Inoreader Integration
- [x] Sidebar count
- [x] Text size configuration
- [x] Text font style configuration (Currently has Playfair Display, Muli, Open Sans and Roboto Slab)
- [x] Supports categorizing of the feeds.
- [x] macOS touchbar shortcuts

## Roadmap
- [ ] Feedbin, Feedly and Inoreader full sync
- [x] New brand name and icons
- [x] Text configuration
- [ ] Supporting authenticated feeds
- [ ] Feedly synchronization
- [ ] Web app
- [x] Pocket Integration

Please feel free to suggest more ideas to improve this app.


## Developer Notes

#### Build Setup

``` bash

# copy config.example.js in renderer to config.js by executing cp config.example.js config.js and set Mercury parser token
cp src/renderer/config.example.js src/renderer/config.js

# install dependencies
yarn install

# serve with hot reload at localhost:9080
yarn dev

# build electron application for production
yarn build


# lint all JS/Vue component files in `src/`
yarn run lint

```

For more documentation please follow link from [Electron Vue](https://simulatedgreg.gitbooks.io/electron-vue/content/)

## Powered by

- [Electron Vue](https://github.com/SimulatedGREG/electron-vue)
- [Bootstrap](https://getbootstrap.com)
- [Vue](https://www.vuejs.org) & [Vuex](https://vuex.vuejs.org)
- [NeDB](https://github.com/louischatriot/nedb)
- [Mercury Parser](https://mercury.postlight.com/web-parser/)


## License
[LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.en.html)
