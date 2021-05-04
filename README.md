[![Arch Linux AUR Package](https://img.shields.io/aur/version/geforcenow-electron?logo=arch-linux&logoColor=white)](https://aur.archlinux.org/packages/geforcenow-electron/)

[![Support this on Patreon](https://raw.githubusercontent.com/hmlendea/readme-assets/master/donate_patreon.png)](https://www.patreon.com/hmlendea) [![Donate through PayPal](https://raw.githubusercontent.com/hmlendea/readme-assets/master/donate_paypal.png)](https://www.paypal.com/donate?hosted_button_id=6YVRGJHDGWGKQ)

# About

GeForce Now application written in Electron, wrapping around the GFN web browser implementation.

# Manual Installation

 - Go to the [latest release](https://github.com/hmlendea/geforcenow-electron/releases/latest).
 - Download the specific file that best fits your disto.

# Usage

If you've installed it through your package manager, then it should already contain a launcher for it. Otherwise, run the `geforcenow` binary.

To toggle full-screen mode, use the `Super + F` keyboard shortcut.

# Building from source

## Requirements

You will need to install [npm](https://www.npmjs.com/), the Node.js package manager. On most distributions, the package is simply called `npm`.

## Cloning the source code

Once you have npm, clone the wrapper to a convenient location:

```
git clone https://github.com/hmlendea/geforcenow-electron.git
```

## Building

```
cd geforcenow-electron
npm install
npm start
```

On subsequent runs, `npm start` will be all that's required.

## Updating

Simply pull the latest version of master and install any changed dependencies:

```
cd geforcenow-electron
git checkout master
git pull
npm install
npm start
```

[![Support this on Patreon](https://raw.githubusercontent.com/hmlendea/readme-assets/master/donate_patreon.png)](https://www.patreon.com/hmlendea) [![Donate through PayPal](https://raw.githubusercontent.com/hmlendea/readme-assets/master/donate_paypal.png)](https://www.paypal.com/donate?hosted_button_id=6YVRGJHDGWGKQ)
