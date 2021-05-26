# Cryptic Wallet

![Download Count](https://img.shields.io/github/downloads/cryptic-network/cryptic-wallet-proton/total.svg)
![Open Issue Count](https://img.shields.io/github/issues/cryptic-network/cryptic-wallet-proton)
![License](https://img.shields.io/github/license/cryptic-network/cryptic-wallet-proton)
![Version](https://img.shields.io/github/v/release/cryptic-network/cryptic-wallet-proton)

<img src="https://raw.githubusercontent.com/cryptic-network/cryptic-wallet-proton/master/screenshots/screenshot.png">
<p>
  Cryptic Wallet is a Cryptic wallet that uses <a href="http://electron.atom.io/">Electron</a>, <a href="https://facebook.github.io/react/">React</a>, and <a href="https://github.com/turtlecoin/turtlecoin-wallet-backend-js">Turtlecoin-Wallet-Backend-JS</a>.
</p>

## Development Setup (All Platforms)

### Dependencies

#### You will need the following dependencies installed before you can proceed to the "Setup" step:

- Node.JS (latest LTS 14.x) https://nodejs.org/

- Yarn https://yarnpkg.com/en/

- Git https://git-scm.com/downloads

Tip: If you already have a different version of node.js installed besides 14.x, try using [Node Version Manager](https://github.com/nvm-sh/nvm#install--update-script).

#### Setup

First, clone the repo via git:

```bash
git clone https://github.com/cryptic-network/cryptic-wallet-proton.git
```

And then install the dependencies with yarn.

```bash
$ cd cryptic-wallet-proton
$ yarn
```

Run the wallet.

```bash
$ yarn start
```

### Starting Development

Start the app in the `dev` environment. This starts the renderer process in [**hot-module-replacement**](https://webpack.js.org/guides/hmr-react/) mode and starts a webpack dev server that sends hot updates to the renderer process:

```bash
$ yarn dev
```

### Packaging

To package apps for the local platform:

```bash
$ yarn package
```

## License

All of the code is released under the GPLv3 license.
See included License file for more details.
© [ExtraHash](https://github.com/ExtraHash)
