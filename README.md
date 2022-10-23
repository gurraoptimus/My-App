[![GPL-3.0 License][license-shield]][license-url] [![Appveyor Build][appveyor-shield]][appveyor-url]

<br />
<p align="center">
  <a href="https://github.com/gurraoptimus/Electron">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Electron app on win32</h3>

  <p align="center">
    My First Electron app on win32.
    <br />
    <a href="https://github.com/gurraoptimus/Electron/issues">Report Bug</a>
    ·
    <a href="https://github.com/gurraoptimus/Electron/issues">Request Feature</a>
    ·
    <a href="#installation"><b>INSTALLATION INSTRUCTIONS</b></a>
  </p>
  

<!-- TABLE OF CONTENTS -->
## Table of Contents
* [Installation](#installation)
  * [Prerequisites](#prerequisites)
  * [Setup](#setup)
* [Contributing](#contributing)
* [License](#license)


## Installation
Build an Electron App in Under 60 Minutes.
### Setup Instructions (click)

[![Build an Electron App in Under 60 Minutes.](https://i.ytimg.com/vi/kN1Czs0m1SU/hqdefault.jpg?sqp=-oaymwEXCNACELwBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLDBoMrwt6kqnnQqtZS6RaJvTmFPmw)](https://www.youtube.com/watch?v=kN1Czs0m1SU "Build an Electron App in Under 60 Minutes.")

## Prerequisites

This is an example of how to list things you need to use the software and how to install them.

[Node.js](https://nodejs.org/en/download/)
```sh
npm init
```

## Setup

1. Clone the repo
```sh
git clone https://github.com/gurraoptimus/Electron.git
cd Electron
```
2. Install NPM electron packages
```sh
npm install --save electron
```
## Serve
3. Run electron
```JS
npm start
```
4. Install NPM packages
```sh
npm install --save-dev electron-packager
```

5. ## Shortcuts
```sh
   ,"package-mac": "electron-packager . --overwrite --platform=darwin --arch=x64 --icon=assets/icons/mac/icon.icns --prune=true --out=release-builds",
"package-win": "electron-packager . electron-tutorial-app --overwrite --asar=true --platform=win32 --arch=ia32 --icon=assets/icons/win/icon.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName=\"ElectronApp\"",    
"package-linux": "electron-packager . electron-tutorial-app --overwrite --asar=true --platform=linux --arch=x64 --icon=assets/icons/png/icon.png --prune=true --out=release-builds"
```

## To Package & Build

  For Windows
```sh
$ npm run package-win
```
For macOS
```sh
$ npm run package-mac
```
For Linux
```sh
$ npm run package-linux
```

<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.


[license-shield]: https://img.shields.io/github/license/gurraoptimus/Electron.svg?-style=flat-square
[license-url]: https://github.com/gurraoptimus/Electron/blob/main/LICENSE
[appveyor-shield]: https://img.shields.io/appveyor/build/gurraoptimus/Electron
[appveyor-url]: https://ci.appveyor.com/project/gurraoptimus/electron



