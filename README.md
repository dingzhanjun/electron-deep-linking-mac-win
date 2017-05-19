# electron-deep-linking-osx


Open app and pass parameters with deep linking using Electron (macOS/win32).

![](https://github.com/oikonomopo/electron-deep-linking-osx/blob/master/electron-deeplinking-osx-example.gif)

This app is registered as ```myapp://```. For example, open Safari browser, enter ```myapp://param``` at address bar. Then 'electron-deep-linking-osx' app will start!

This is based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation, then followed [‘electron-builder’ quick-setup-guide](https://github.com/electron-userland/electron-builder#quick-setup-guide) to produce macOS/win32 installer

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/oikonomopo/electron-deep-linking-osx.git
# Go into the repository
cd electron-deep-linking-osx
# Install dependencies
npm install
# Run the app
npm start
# Produce installer
npm run dist
```
After running the installer (at electron-deep-linking-osx/dist/), you can try to open 'electron-deep-linking-osx' app with deep linking, by entering ```myapp://param``` at Safari address-bar.

## License

[GNU GPLv3](LICENSE.md)
