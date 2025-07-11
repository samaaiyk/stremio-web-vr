# Stremio - Freedom to Stream

![Build](https://github.com/stremio/stremio-web/workflows/Build/badge.svg?branch=development)
[![Github Page](https://img.shields.io/website?label=Page&logo=github&up_message=online&down_message=offline&url=https%3A%2F%2Fstremio.github.io%2Fstremio-web%2F)](https://stremio.github.io/stremio-web/development)

This Streamio Fork makes it easier to be able to run Stremio Web on VR Web Browsers, especially PCVR like Heresphere, DeoVR, etc. Simply serve the build (or host it somewhere) and open the link in the web browser of your favourite VR Player.

## Fork Changes
* Real Debrid is added in whitelist to make sure the download link works
* Download button directly added on the right side of Stream Links, for convenience

## Build

### Prerequisites

* Node.js 12 or higher
* npm 6 or higher

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm start
```

### Production build

```bash
npm run build
```

## Screenshots

### Download Button

<img width="502" height="456" alt="{4F1C93F4-53F0-4A07-9C08-CC223EA5665E}" src="https://github.com/user-attachments/assets/b5b9323a-35c6-4002-94d0-86ee9b580b3b" />


### Board

![Board](/screenshots/board.png)

### Discover

![Discover](/screenshots/discover.png)

### Meta Details

![Meta Details](/screenshots/metadetails.png)

## License

Stremio is copyright 2017-2023 Smart code and available under GPLv2 license. See the [LICENSE](/LICENSE.md) file in the project for more information.
